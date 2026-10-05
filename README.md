# interactor-game-tag-starvote-ballots

Picks a set of standout games from a market-research table by a score-voting election, with a sales metric as each ballot's score.

## What it is for

Each row of the table becomes a ballot that scores its own game by the chosen metric. A score-voting election then picks the winners and prints each with its tags, to show which tag combinations lead a genre.

## Build and run

```sh
pip install -r requirements.txt
just run
```

`python3 game_tag_election.py --help` lists the column and candidate options.

## Licence

MIT; see `LICENSE`.
