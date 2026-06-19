# 🛒 Olist E-Commerce — Business Performance Analysis

## Project Overview :exclamation::exclamation:
After going through Christine Jiang's EDA framework on the [GameZone dataset](https://github.com/vittokevin/gamezone-sales-trends-eda), this was the first real test of whether that process actually stuck. No tutorial to follow, no guided steps, just a dataset and a clock.

The challenge was simple: given 5 files from the Olist dataset, a real Brazilian e-commerce platform, figure out what the data is saying and surface business performance insights within 5 hours. The goal was to stay focused, avoid going down rabbit holes, and come out with findings that actually mean something to the business, specifically operations and sales.

4 key findings made the cut. Everything else got left out on purpose.

## :question: Objectives  
The main goal was to test whether the EDA process from the GameZone project could actually be applied independently, under time pressure, on a real dataset.

Specifically, I wanted to:
- Stay focused and avoid analysis paralysis within a 5 hour window
- Define a clear scope before touching the data instead of just diving in
- Identify findings that are relevant to a specific business audience (sales and operations team)
- Practice moving from raw data to structured insights without a guided framework to follow
- Find out where the gaps in my EDA skills still are when there's no safety net

## :computer: Tools and Technologies
- Excel

## :floppy_disk: Methodology
Methodology
Given the 5 hour time limit, the approach was straightforward: scope first, then execute, then document what was usable.

Scoping the Analysis
Before touching anything, the focus was narrowed down to two core business areas: revenue performance for sales and order volume for operations. That decision alone cut out a lot of noise and made the rest of the analysis much more directed.

Connecting the Data
[Five files](https://1drv.ms/f/c/8b165763c3e5efed/IgDuqJBLU9dYTZlxvvKzmGOjATuEh69byqhwlol19dy-m5o?e=I7geh6) from the Olist dataset were used:

olist_orders_dataset

olist_order_payments_dataset

olist_order_items_dataset

olist_order_reviews_dataset

olist_products_dataset

VLOOKUP was used to connect the relevant tables together so the data could be analyzed as a single picture rather than five separate pieces.

### Building the Analysis
Pivot tables were the main tool for summarizing revenue and order volume by month. Other essential formulas were layered in to calculate and surface the specific metrics needed for each finding.

### Documentation
A [summary insights log](https://1drv.ms/x/c/8b165763c3e5efed/IQDabUpxAcQnQqGxFOg9kfDfAUMmlSSu2k0wQaQ7njd64h0?e=eBGwFJ) was created to capture the key findings. A full detailed log wasn't possible within the time limit, but the priority was making sure the output was usable and the findings were clear.

## :collision: Key Insights 
The full breakdown of these findings is documented in a [write-up](https://1drv.ms/w/c/8b165763c3e5efed/IQCcMO7EsaUFTpscSN7rhFTCAV11ViwhuodfLNnEq2o2kJY?e=sfzIMi) included in this repository.

## :sparkles: Reflection
The biggest test of this project was whether the habits from the GameZone project would actually hold up under time pressure.

The short answer is mostly yes. Scoping the focus to revenue and operations before opening any file made a real difference. Without that, 5 hours would have disappeared fast. Having a direction meant every decision had a filter, what's relevant to the scope stays, everything else gets skipped.

The part that took the most discipline was stopping. When the furniture category finding came up and the review data started pointing toward late deliveries, there was a pull to keep digging. But with a hard time limit, knowing when a finding is good enough to include and moving on is just as important as finding it in the first place.

The one thing that didn't survive the time pressure was a proper insights log. A summary got done, but a full running log wasn't realistic in 5 hours. That's a gap worth filling in future projects where time isn't as tight.

Overall this confirmed that the EDA process works even when the conditions aren't ideal. The framework holds up. The execution just gets leaner.

## :star: Future Improvements
This project was a good stress test, but there are a few things worth improving for next time.

### Build a proper insights log even under time pressure
The summary log got the job done, but a running log built as the analysis progressed would have made the write-up faster and more structured. Even a rough version is better than piecing it together at the end.

### Get faster at connecting multiple datasets
The VLOOKUP step took longer than it should have. That friction is actually what pushed me to start learning Power Query, which handles data connections a lot more efficiently than manual lookups across multiple files.

### Push the findings one level deeper
The 4 findings were solid for a 5 hour window, but each one has more to it. The late delivery and bad review connection especially deserves a closer look, like which regions or sellers are driving it most.

### Keep applying this to real datasets
The Olist dataset was a big step up from GameZone in terms of complexity and business relevance. The plan is to keep working with real world data, including my sister's small business, to keep building that instinct for what matters and what doesn't.
