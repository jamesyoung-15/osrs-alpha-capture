# Old School Runescape Investment Alpha Capture System

Ongoing project for investment recommendation for Old School Runescape items based on recent sub-Reddit posts in r/GrandExchangeBets and r/OSRSflipping. 

Basically recommends a list of items to buy/sell based on recent Reddit posts and analysis of price change before and after the post.

Idea from Alpha Capture System (used by hedge funds).

## Brainstorm Ideas

Alpha Capture System:

- Scrape recent Reddit posts (maybe like recent 20) from either OSRS investing sub-Reddits, or track recommendations from Reddit users.
- Find keywords with relevant OSRS items, need a way to also include slangs (eg. ZCB -> Zaryte crossbow), may need to manually add slangs/acronyms for items
- Check price history of items with OSRS Wiki API for Markout. Analysis part need more research
- Based on analysis, decide whether to recommend a buy/sell on item

App Idea:

- Frontend displays list of buy/sell items for each half-day (don't want to do real-time to avoid API limit and computation costs, so not really a true alpha-capture system)
