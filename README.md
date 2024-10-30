# KotobaBot Importer

This tool extracts Japanese words from text and prepares them for import into KotobaBot via CSV exports. I personally use it on **[NHK Easy](https://www3.nhk.or.jp/news/easy/)** 

https://k0gasa.github.io/KotobaBot-Deck-Maker/

## Overview

It takes Japanese text and turns it into a personalized vocabulary list. Paste your Japanese text, and it will:

- Break down the text into individual words.
- Fetch pronunciations, meanings, and JLPT levels for each word.
- Allow you to add words manually if something is missing.
- Export the list in a CSV format ready for KotobaBot.

## How to Use

1. **Paste Your Text**: Copy any Japanese text you want to study and paste it into the textarea on the main page.

2. **Extract Words**: Click the "Extract Words" button. The tool will segment the text into words and fetch data for each one.

3. **Review the Word List**: Click the ☰ menu button to open the sidebar and see all the words. Here you can:

   - View pronunciations, meanings, and JLPT levels.
   - Add new words manually.
   - Remove words you don't need.

4. **Export Your List**: When you're ready, click "Export" in the sidebar to download a CSV file.

5. **Import into KotobaBot**: Use the exported CSV file to import the words into **[KotobaBot](https://kotobaweb.com/dashboard)** on Discord.

## Features

- **Automatic Word Extraction**: Uses TinySegmenter to split Japanese text into individual words, filtering out common particles and short words.

- **Word Data Fetching**: Automatically fetches pronunciation, meaning, and JLPT level for each word using the JLPT Vocab API.

- **Manual Word Addition**: Add words manually if they're not recognized or if you want to include something specific.

- **Import/Export Functionality**: Save your word list and load it back up whenever you need.

## Tips

- **Adding Words Manually**: If a word isn't found automatically, you can add it manually by clicking the "Add" button in the sidebar and filling in the details.

- **Sidebar Navigation**: Click outside the sidebar to close it, or pin it open using the 📌 icon if you want it to stay open.

- **Data Import**: You can import a previously saved list by clicking "Import" in the sidebar and pasting your JSON data.

## Acknowledgements

- **[TinySegmenter](https://github.com/takuyaa/tiny-segmenter)**: For splitting Japanese text into words.

- **[JLPT Vocab API](https://jlpt-vocab-api.vercel.app/)**: For fetching word data like pronunciation and meaning.
