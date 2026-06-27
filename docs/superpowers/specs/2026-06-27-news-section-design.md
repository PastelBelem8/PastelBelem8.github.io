# Homepage News Section — Design

**Date:** 2026-06-27
**Status:** Approved

## Goal
Add a "News" section to the homepage (`_pages/about.md`) that shows recent,
dated updates (papers, talks, internships, programs) in a compact, scrollable
box — matching the convention on academic homepages such as
fywalter.github.io and isthatyou.github.io.

## Placement
Directly after the bio in `_pages/about.md`, under a `## News` heading.

## Item format
Date-prefixed: a **bold "Mon YYYY"** date, an em dash, then the entry text with
inline links. Newest first.

## Display behavior
A fixed-height container (~5 items tall) with an internal vertical scrollbar for
older entries, so the homepage stays compact as the list grows.

## Architecture (data-driven)
Three pieces, each with one responsibility:

1. **`_data/news.yml`** — the content. A list of entries:
   ```yaml
   - date: 2026-05-01            # real date; used for sorting and display
     content: "New preprint available: [Certainty Distortion in Language Model Rewriting](https://arxiv.org/pdf/2606.07951)"
   ```
   `content` is Markdown (inline links allowed). `date` is a full `YYYY-MM-DD`.

2. **`_includes/news.html`** — the renderer. Sorts entries by `date` descending,
   formats each date as `%b %Y` ("May 2026"), renders `content` through
   `markdownify` (stripping the wrapping `<p>`), and emits the scroll-box markup:
   ```liquid
   {% assign news_sorted = site.data.news | sort: "date" | reverse %}
   <div class="news-list">
     {% for item in news_sorted %}
       <div class="news-item">
         <span class="news-date">{{ item.date | date: "%b %Y" }}</span>
         <span class="news-text">{{ item.content | markdownify | remove: "<p>" | remove: "</p>" }}</span>
       </div>
     {% endfor %}
   </div>
   ```

3. **`_sass/_custom.scss`** — the styling. A `.news-list` scroll box and
   `.news-item` / `.news-date` / `.news-text` rules, all using the brand
   `--global-*` variables (pale blue-gray `#EAF0F6` background via
   `--global-code-background-color`, cool-gray `#CAD4DF` border, deep-slate bold
   date, muted-blue links inherited from the theme).

`_pages/about.md` references the section with `## News` + `{% include news.html %}`.

## Seed entries (newest first)
| date (YYYY-MM-DD) | display | content |
|---|---|---|
| 2026-06-01 | Jun 2026 | Participating in the Deep Voices program from DLSPT (remote) |
| 2026-05-01 | May 2026 | New preprint available: [Certainty Distortion in Language Model Rewriting](https://arxiv.org/pdf/2606.07951) |
| 2026-01-15 | Jan 2026 | Paper accepted at ICLR 2026: *Uncertainty as Feature Gaps* |
| 2025-06-15 | Jun 2025 | Started a research internship at Apple |
| 2025-06-01 | Jun 2025 | Started a research internship at Capital One |
| 2025-04-01 | Apr 2025 | Invited talk at the Mila/McGill NLP reading group on *Perceptions of Linguistic Uncertainty* ([details](https://mcgill-nlp.github.io/reading-group/winter-2025/catarina-belem/)) |
| 2025-03-01 | Mar 2025 | New preprint available: *Semantic Probabilistic Control of Language Models* |
| 2025-01-01 | Jan 2025 | Paper published in *Nature Machine Intelligence* |
| 2024-11-01 | Nov 2024 | EMNLP 2024 main-conference paper: *Perceptions of Linguistic Uncertainty* |
| 2024-06-01 | Jun 2024 | Started a research internship at Megagon Labs |

Note: Apple and Capital One are both dated Jun 2025 per the user; distinct `date`
day values keep their ordering stable while both display "Jun 2025".

## Out of scope
- No separate `/news/` archive page.
- No automatic generation of news from the publications/talks collections.
- No per-item icons or tags.

## Files touched
- `_data/news.yml` (new)
- `_includes/news.html` (new)
- `_pages/about.md` (edit: add News section)
- `_sass/_custom.scss` (edit: add `.news-list` styles)
