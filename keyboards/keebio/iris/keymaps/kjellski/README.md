This is for you kjellski, you wrote it!

1. Go to https://config.qmk.fm/#/keebio/iris/rev2/LAYOUT and import the `kjellski.json` file.
2. Modify to your liking and export to `kjellski.json` again - or rename to something like `kjellski_v2.json`.
3. To go from JSON to .c file: `qmk json2c kjellski.json > keymap.c`
4. Build the layout: `qmk compile -kb keebio/iris/rev2 -km kjellski`
5. Flash with the toolbox app - connect keyboard, press reset button on keyboard, press flash button in toolbox app!
