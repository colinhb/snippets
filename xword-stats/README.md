# xword-stats

This project has a few phases. 

The first is using [mattdodge/nyt-crossword-stats](https://github.com/mattdodge/nyt-crossword-stats) to download a `data.csv` crossword data file from the NY Times. This is self-documented in the `mkfile`, but requires a valid `NYT-S` cookie from nytimes.com in a `.env` file.

The second is using an Observable notebook [@colin8/xword-stats](https://observablehq.com/@colin8/xword-stats) to visualize `data.csv`, plotting solve times with a series for each weekday (difficulty) and a rolling median.

![Solve times by weekday with rolling median](observable-plot.png)
