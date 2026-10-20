# Hi, I'm Swayam Gupta

Software engineer in Bengaluru, open to remote. I work on browser automation, web scraping and systems code in Python, C and C++, and I contribute to open-source projects.

**What I work on**
- **Browser automation and scraping:** Playwright, Selenium and Scrapy pipelines, session handling, and pulling structured data out of web apps
- **Systems:** C/C++ performance work in storage engines, a toy compiler, reverse engineering and binary parsing
- **Backend and integrations:** REST API clients, OAuth/SCIM app integrations, rate-limited batch jobs, Django

**Currently learning:** Rust and Apache DataFusion

## Selected open-source contributions (merged)

| Project | Contribution |
|---|---|
| [TidesDB](https://github.com/tidesdb/tidesdb) (C storage engine) | [#643](https://github.com/tidesdb/tidesdb/pull/643): faster SHA256 `update`/`final` (block-wise `memcpy` instead of per-byte copies) plus benchmark tests |
| | [#658](https://github.com/tidesdb/tidesdb/pull/658): compile SHA256/HMAC code and their tests only into S3-enabled builds |
| [Scrapy](https://github.com/scrapy/scrapy) | [#6547](https://github.com/scrapy/scrapy/pull/6547): moved tool configs into `pyproject.toml` (14 files) |
| [zyte-common-items](https://github.com/zytedata/zyte-common-items) | [#118](https://github.com/zytedata/zyte-common-items/pull/118): migrated `setup.py` to `pyproject.toml` |
| | [#115](https://github.com/zytedata/zyte-common-items/pull/115): fixed the tox command so tests report coverage |
| [Zulip](https://github.com/zulip/zulip) (Python/Django) | [#28516](https://github.com/zulip/zulip/pull/28516): stopped exposing email addresses as URL parameters on the find-account page |
| | [#28582](https://github.com/zulip/zulip/pull/28582): added a "send another email" button to find-account |
| | [#28598](https://github.com/zulip/zulip/pull/28598): send an email even when no Zulip account matches the address |
| | [GoCD integration rewrite](https://github.com/zulip/zulip/commit/6c583c9bfe4c56fe7b655494b403156d3498ac1d) (co-authored): moved to a webhook-plugin-based integration with richer notifications, fixtures and tests (fixes #21224) |

## Projects

- **[Notion-Playwright](https://github.com/swayam0322/Notion-Playwright)**: async Playwright script that logs into Notion, reuses the saved session, invites test members, and exports workspace users to JSON through Notion's web endpoints.
- **[simplelang](https://github.com/swayam0322/simplelang)**: small C++ compiler (tokenizer → recursive-descent parser → AST → assembly for a simple two-register machine), written to learn compiler basics.
- **[smartlead](https://github.com/swayam0322/smartlead)**: threaded, rate-limited Python client that finds and removes leads that never replied from completed SmartLead campaigns. Uses Polars and a GitHub Actions workflow.

## Tech

Python (Playwright, Scrapy, Selenium, BeautifulSoup, Requests, Polars, Django) · C · C++ · CMake · JavaScript/TypeScript · MongoDB · Firebase · SQL/MySQL · Git & GitHub Actions · Linux

## Contact

[LinkedIn](https://www.linkedin.com/in/swayam0322/) · [GitHub](https://github.com/swayam0322)
<!-- Optional: add an email address you want recruiters to use, e.g. mailto link. X: @_thehoodieguy_ (include only if you want it on a job-facing page). -->
