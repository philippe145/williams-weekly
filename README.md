# Williams College Weekly Analysis

Williams College alpine skiing compared with the EISA league, slalom and giant slalom.

Live page: https://philippe145.github.io/williams-weekly/

- **Official EISA standings**: cumulative EISA points (50, 47, 44, 41, 39 ... per place; best three per team per race), by leg and all alpine.
- **Speed x finish index** (60/40): winner's time / racer's time x 100, best three per team per race, plus the share of clean runs.
- **Points left on the hill**: a model estimate, each DNF/DSQ placed at that racer's median speed in the discipline and re-scored. Not a result.
- **Ephs**: every Williams racer's race-by-race results (run 1 vs run 2, place, points).

## Data
`data/races.json` holds one record per race and gender with every starter's run times, team and EISA points. Sources: Bullitt Timing result sheets (data.bullitttiming.com); the 2025-26 St. Lawrence carnival comes from FIS race pages (points for teams other than Williams reconstructed). Course data from FIS. `data/carnivals.json` holds the official team-score sheets. A weekly update adds new carnivals each Monday from January 2027.

All figures are computed in the page from the stored results.
