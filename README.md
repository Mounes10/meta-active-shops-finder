# Meta Active Shops Finder

**A keyword-free ad spy tool concept to discover potential untapped and winning products through Meta Ad Library.**

> Community project proposal seeking volunteer contributors. No working software is available yet.

## The idea

I want a system that automatically discovers ecommerce shops advertising on Facebook and Instagram, keeps only shops running **more than 70 active ads**, and displays their **website URLs directly in the results** so I can explore their products.

The goal is to find promising products and less-explored opportunities without having to guess search keywords or already know which brands to investigate.

The format is completely open: a website, browser extension, desktop app, script, or any practical system.

## Essential requirements

- **No keyword search required.** Discovery should work without entering product names, keywords, competitor names, or a predefined shop list. Optional country or other non-keyword filters are fine.
- Use publicly accessible Meta Ad Library information to discover shops and their ads. A keyword-free Meta results URL may be a starting point if technically viable.
- Collect all accessible results within the chosen scope, rather than stopping at the first screen.
- Keep only shops with **71 or more active ads**. A shop with exactly 70 does not qualify.
- Display each shop’s actual website URL on the results page, with its name, active ad count and Meta source link.
- Remove duplicate shops and sort by active ad count, highest first.
- Make it easy to inspect the advertised products through available ad links and product landing pages.

## Desired output

| Shop | Shop website URL | Active ads | Meta source | Product / ad links | Last checked |
| --- | --- | --- | --- | --- | --- |
| Example shop (fictional) | https://shop.example | 95 | Advertiser page | Available links | Collection date |

Copying all shop URLs and exporting a CSV would be useful additions.

## What “untapped” and “winning” mean here

These are **research goals and candidate signals**, not guaranteed outcomes. Meta’s public ad data does not establish sales or profitability, and a high shop-level ad count does not prove that any individual product is a winner.

A later version could help prioritize candidates using clearly explained signals such as ad longevity or repeated product promotion. Any low-competition or “untapped” indicator would need its own evidence and a defined market scope; the 71+ filter alone is not a saturation measure.

## First prototype and feasibility

The first milestone is to establish a workable **keyword-free discovery method** and demonstrate a small, verifiable list of qualifying shops. This is a requirement to investigate, not a claim that Meta exposes an exhaustive directory.

Count distinct active ad IDs within a stated geographic scope, record the collection time, and flag incomplete counts or unresolved shop URLs. Explain coverage limits instead of claiming to cover every shop on Meta. How to associate multiple advertiser pages with one shop should be agreed during prototyping.

## Volunteer contributors welcome

This is a community idea with **no development budget**. Contributions are voluntary and there is no imposed technology or delivery deadline.

Help is welcome with:

- validating keyword-free discovery feasibility;
- choosing the simplest technical approach;
- building a small prototype;
- checking ad counts and shop URLs against public source pages.

Please use this repository’s **Discussions** for ideas and feasibility feedback, and **Issues** for concrete tasks. The future code’s open-source license should be agreed before code contributions begin.
