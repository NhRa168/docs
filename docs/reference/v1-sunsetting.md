---
title: Sunsetting Dune V1
description: It's been real, but now it's time to say goodbye to our V1 platform.
---

With the release of the Polygon decoded tables on Dune Engine V2, we now have all [Raw](../tables/raw/index.md) and [Decoded](../tables/decoded/index.md) data that was on V1 on V2! 

As a result we have started decommissioning blockchains on V1 as we transition to V2 as our primary platform.

Once a chain is commissioned, queries referncing the V1 version won't be editable anymore until you log in and select DuneV2 from the data explorer drop down to re-run them as V2 queries.

Here's an estimate of the **order** and **dates** by which we plan to **decommission chains** on V1: 

- BSC (decommission by Jan 31st 2023, extended from Dec 14th due to community feedback)
- Polygon (decommission by Jan 31st 2023, extended from Dec 21st due to community feedback) 
- Optimism (decommission completion date TBD, decomission process started Jan 2023) 
- xDai (decommission completion date TBD, decomission process started Jan 2023)
- Ethereum (decommission TBD - estimate kickoff Q1 2023)  

Please also note:

- No new contracts that are submitted for decoding (on all blockchains) will be decoded on V1, they will only be decoded on V2* (already decoded contracts will continue to work as normal) 
- No new Abstraction PRs will be merged on V1* (please use [Spellbook](../spellbook/index.md) on V2)
 
*special cases can be individually reviewed 

## Decommissioning Schedule for Optimism and xDai (Updated Jan 19 2023)

- Week 0 (Jan 19th)
  - Kickoff of the decommissioning, no changes to V1 queries 
- Week 3 (Feb 9)
  - Removal of the blockchain from the blockchain selection dropdown
  - Existing queries are still editable on V1
- Week 6 (March 1st) 
  - V1 queries for the given blockchain will become read only, forking and updating on V2 will be required
  - Data will continue to update and refreshed for the queries on V1
- Week 10 (March 31st)
  - No new data will power queries for the chain on V1, decommission complete

## How Decommissioning will work **in General**

The process below is the same for all blockchains, and will be completed by the above decommissioning dates.

### Week 0

- Kickoff of the decommissioning, no changes to V1 queries

### Week 3

- Removal of the blockchain from the blockchain selection dropdown
- Existing queries are still editable on V1

### Week 6

- V1 queries for the given blockchain will become read only, forking and updating on V2 will be required
- Data will continue to update and refreshed for the queries on V1

### Week 13 
- No new data will power queries for the chain on V1, decommission complete

## To learn more and ask questions

- Check out our [V2 reference doc](../reference/dune-v2/index.md) to learn more about how V2 works.
- Check out our [Data Explorer guide](../app/queries/data-explorer.md) to learn more about how searching in V2 works.
- Watch our [Dune Arcana](https://dune.com/watch) videos for general insights - they all use Dune V2!
- [Join our live Office Hours](https://events.dune.com/) or ask in our [#query-questions Discord channel](https://discord.com/channels/757637422384283659/757641002138730588).

