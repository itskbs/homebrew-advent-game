# Advent-Game

Homebrew tap for [advent-game](https://github.com/itskbs/advent-game), a CLI
advent calendar: one quiz per day, four choices, one correct answer, one
letter earned. Collect all 24 and reveal the solution word on Dec 24.

## Install

```sh
brew tap itskbs/advent-game
brew install advent-game
```

If formular loading is refused:

```sh
brew trust itskbs/advent-game
brew install advent-game
```

## Usage

```sh
advent-game day1        # play today's (or an earlier) puzzle
advent-game status      # see which days you've solved
advent-game solution    # reveal the word from your collected letters
advent-game help
```

## About this repo

`Formula/advent-game.rb` is generated and pushed here automatically by
[GoReleaser](https://goreleaser.com) whenever a new version is tagged in the
[main repo](https://github.com/itskbs/advent-game) — it is not meant to be
edited by hand here. To release a new version, see that repo's
[README](https://github.com/itskbs/advent-game#releasing).
