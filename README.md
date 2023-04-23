# ttrpg-emphasis-roll

This is an interactive menu navigator for Brennan Lee Mulligan's "Emphasis Roll" mechanic for use in Discord.

- A few characters used in the source document have been converted to "UTF-8"-safe characters for general ease of reading on user and code structure, text markup has also been changed to align with Discord's own.
- Names for files were selected based on the content of those files, with the best approximation of what it was described as (and often use literal terminology from the file itself).
- `./router/credits.yml` was added to refer to the section below in Discord as well.

## Credits

There are multiple sources, and I was unable to find the direct reference that ties this to Brennan - so I will list everything that was used to both research it, and anything else that would have been included in its creation.

- [Worlds Beyond Number](https://worldsbeyondnumber.com/)
  - [simplecast.com](https://worlds-beyond-number.simplecast.com/)
  - [Spotify](https://open.spotify.com/show/4xQ4HKZjIg04Phtj2gaTbi)
- [Reddit Post by u/RAINING_DAYS](https://www.reddit.com/r/UnearthedArcana/comments/11yiatw/brennen_lee_mulligans_new_rolling_with_emphasis/)
  - [NaturalCrit Home Brewery](https://homebrewery.naturalcrit.com/share/wyL-vuEIDrbC)

### AnyDice Programs

- [Minimal](https://anydice.com/program/2e749) - [u/WideShining_Thea](https://redd.it/11yif0x) on Reddit
- [Expanded](https://anydice.com/program/2edb6) - [HighDiceRoller](https://rpg.stackexchange.com/a/205724) on RPG Stack Exchange


## Instructions to run

```sh
npm install
# add webhook to env or 'config.json'
# add your files within the repository and specify them directly or use globs
npm run sequence
```

---

If you need any help setting up the environment, [drop by the Discord server](https://discord.gg/Bb3JQQG).