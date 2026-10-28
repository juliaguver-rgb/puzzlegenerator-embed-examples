# PuzzleGenerator embed examples

PuzzleGenerator provides free printable puzzle generators for classrooms, families and KDP creators. This repository contains small, copy-friendly HTML examples for embedding the hosted tools. It is not the PuzzleGenerator source code.

## Live generators

- [Sudoku Generator](https://puzzlegenerator.org/sudoku-generator/)
- [Word Search Generator](https://puzzlegenerator.org/word-search-generator/)
- [Crossword Generator](https://puzzlegenerator.org/crossword-generator/)
- [Maze Generator](https://puzzlegenerator.org/maze-generator/)
- [Cryptogram Generator](https://puzzlegenerator.org/cryptogram-generator/)
- [Word Scramble Generator](https://puzzlegenerator.org/word-scramble-generator/)
- [Kakuro Generator](https://puzzlegenerator.org/kakuro-generator/)

## Basic embed example

Replace YOUR_EMBED_TOKEN with a token generated in your PuzzleGenerator account. The hosted widget keeps the PuzzleGenerator attribution link.

```html
<iframe
  src="https://puzzlegenerator.org/embed/sudoku/?token=YOUR_EMBED_TOKEN"
  title="Sudoku Generator — PuzzleGenerator"
  width="100%"
  height="1000"
  style="border:0;max-width:100%"
  loading="lazy">
</iframe>
<p><a href="https://puzzlegenerator.org/sudoku-generator/" target="_blank" rel="noopener">Powered by PuzzleGenerator</a></p>
```

The same pattern is available for the other generators using their embed route, such as /embed/word-search/ or /embed/crossword/, with the token issued for that tool.

## Notes

- Keep the attribution link in the embed.
- Use responsive width and a height suitable for your page.
- Do not publish private tokens in client-side repositories.
- PDF downloads from the widget are prepared without a logo; the widget itself includes the PuzzleGenerator attribution.

Project website: https://puzzlegenerator.org/
