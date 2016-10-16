# Chess

This repository contains (not yet) all games I played on the [Free Internet Chess Server](http://freechess.org/) (FICS) starting 2007. There will be a collection of these gamesbe accessible in the future at [https://jukey.github.io/chess/](https://jukey.github.io/chess/) (currently there is shown an example game). 

## Format and Directories

The games are stored in [pgn files](https://en.wikipedia.org/wiki/Portable_Game_Notation). There is one file per year I played at lease once. The games are storen in the pgn directory. Starting October 2008 there is a version containing the move times as well available (pgn-including-movetimes). The zip directory contains a zipped version (e.g. for download).

```
.
├── pgn
│   └── ficsgamesdb_jukey_YEAR_nomovetimes.pgn
│   
├── pgn-including-movetimes
│   └── ficsgamesdb_jukey_YEAR_movetimes.pgn
|
└── zip
    ├── ficsgamesdb_jukey_YEAR_movetimes.pgn.zip
    └── ficsgamesdb_jukey_YEAR_nomovetimes.pgn.zip

```

## How to import the game data from the fics servers

There is a wonderful website, called [ficsgames.org](http://ficsgames.org/) available for all games ever played on the [Free Internet Chess Server](http://freechess.org/). In order to download game data do

- Go to the [download section of the page](http://ficsgames.org/download.html)
- Enter `jukey` at the *Games of player:* input field
- Select a `year` and *whole year* as `month`
- (optional) Select the `include move times` radio button
- After a few seconds you get a link to download a zip file containing the pgn for the selected year
