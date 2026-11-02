# Website AI Visibility Data

Public company lists from Scott King's research into how websites show up to AI search and answer engines (ChatGPT, Perplexity, Google AI Overviews and others).

Each study gets its own folder. The lists show which sites were measured. They do not include the measurement results.

The measurement results are at https://thescottking.com/what-ai-search-engines-see-b2b-software-websites

By [Scott King](https://thescottking.com) · [LinkedIn](https://www.linkedin.com/in/thescottking/)

## Datasets

| Folder | What it is | Sites | Measured |
|---|---|---|---|
| [`2026-10-ai-crawler-access`](2026-10-ai-crawler-access/) | B2B software and services company websites checked for AI crawler access, llms.txt, structured data and related signals | 3,925 | October 2026 |

## Columns (`companies.csv`)

| Column | Meaning |
|---|---|
| `name` | Company name |
| `domain` | Website domain that was measured |
| `website_url` | Homepage URL |
| `linkedin_url` | Company LinkedIn page, where known |
| `sic_codes` | SIC industry codes, separated by `\|` when there is more than one |
| `naics_codes` | NAICS industry codes, separated by `\|` when there is more than one |
| `founded_year` | Year founded, where known |
| `city`, `state`, `country` | Headquarters location, where known (often blank) |

Rows are sorted alphabetically by company name. The order carries no meaning.

Company details come from a commercial company database and may be incomplete or out of date. Corrections are welcome through an issue or pull request.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Use it however you like, and credit "Scott King, thescottking.com" with a link back to this repo.
