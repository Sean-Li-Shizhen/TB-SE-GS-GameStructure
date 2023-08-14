# TB-SE-GS-GameStructure
Attempts to validate the ideas of a more real grand strategy game design, being Turn-Based (enough time for deep thoughts), Sametime-Execution (action sequence don't come into play).

## Major Difference against Major Grand Strategy Games

Not being a full-time game player, I do not have super huge knowledge of all the existing strategy games. I will only talk about some grand strategy games I personally have experience with to discuss.

Civilization Series (Civ6):
The full map is tiled with hexagons, and everything is based on tiles. Districts/enhancements got placed on tiles, troops controls a full tile, citizens works on tiles. I could say, its map is a hyper digitized version of a detailed map and thus lose information.
Distribution of production and consumption based on cities, further distribution is not apparent until enemy troops are placed on top of a tile.
Long being joked about thousand-year-long wars. Battles and civilization growth shouldn't be on the same timescale.
Turn based with a defined sequence of player action, the later player have more or less some disadvantage.
Type: Standard Turn-Based

Paradox Interactives (existing powers -- Europa Universalis 4, growth from one place -- Stellaris):
Free-running time (with user decided pause for thinking, not OK in multiplayer).
production is distributed, but consumption is centralized, total production to be used by total pop all at once at a tick of the timer.
Low freedom with predefined regions/connections, predefined objectives, and predefined local special mechanics, full on it is a "history simulator".
Type: Real-time Strategy

Total Wars (Napoleon):
Seperated Strategy and Tactic, strategies like trade, diplomacy, Growth are managed externally in a turn-based behavior, and battles are fought within the turn as real time strategy. Solves timescale problem while, making it into two games.

## Provisioned Gameplay Procedure

* At the start of each turn, control is given to each of the player/AI.
* At certain turns (10 turns just for saying), strategy decisions are to be made, including diplomacy, manpower management.
* At every turn, military decisions are to be made, ordering troops to perform actions. In peaceful times this should be very quick with mostly "keep the last order".
* After every player/AI admitted end-of-turn, all executions are to happen at the same time, first diplomatic actions like alliance/war declaration are presented/informed, then military movements are executed as determined before. During the execution no change can be made and can only watch things happen.


