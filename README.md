# PuzzleGenerator embed examples

PuzzleGenerator provides free printable puzzle generators for classrooms, families and KDP creators. This repository contains copy-friendly HTML examples for embedding the hosted tools. It is not the PuzzleGenerator source code.

## Embed endpoints

Each widget uses the same iframe pattern. Replace YOUR_EMBED_TOKEN with a token created in your PuzzleGenerator account.

| Tool | Embed route |
| --- | --- |
| Sudoku | `/embed/sudoku/` |
| Word Search | `/embed/word-search/` |
| Crossword | `/embed/crossword/` |
| Word Scramble | `/embed/scramble/` |
| Maze | `/embed/maze/` |
| Cryptogram | `/embed/cryptogram/` |
| Kakuro | `/embed/kakuro/` |

Example:

```html
<iframe src="https://puzzlegenerator.org/embed/sudoku/?token=YOUR_EMBED_TOKEN" title="Sudoku Generator — PuzzleGenerator" width="100%" height="1000" style="border:0;max-width:100%" loading="lazy"></iframe>
<p><a href="https://puzzlegenerator.org/sudoku-generator/" target="_blank" rel="noopener">Powered by PuzzleGenerator</a></p>
```

For another tool, change both the embed path and the attribution link. Keep the attribution link in every installation.

## Main generators

- [Sudoku Generator](https://puzzlegenerator.org/sudoku-generator/) · [6×6 Sudoku](https://puzzlegenerator.org/sudoku-generator-6x6/) · [4×4 Sudoku](https://puzzlegenerator.org/sudoku-generator-4x4/) · [9×9 Sudoku](https://puzzlegenerator.org/sudoku-generator-9x9/) · [16×16 Sudoku](https://puzzlegenerator.org/sudoku-generator-16x16/)
- [Word Search Generator](https://puzzlegenerator.org/word-search-generator/) · [Random Word Search](https://puzzlegenerator.org/random-word-search-generator/) · [AI Word Search](https://puzzlegenerator.org/ai-word-search-generator/) · [Word Search from Image](https://puzzlegenerator.org/word-search-from-image/) · [Word Search Solver](https://puzzlegenerator.org/word-search-solver/)
- [Crossword Generator](https://puzzlegenerator.org/crossword-generator/) · [Random Words Crossword](https://puzzlegenerator.org/random-words-crossword-generator/) · [Bulk Crossword](https://puzzlegenerator.org/bulk-crossword-generator/) · [AI Crossword](https://puzzlegenerator.org/ai-crossword-generator/) · [American Grid Crossword](https://puzzlegenerator.org/american-grid-crossword-generator/) · [Crossword Solver](https://puzzlegenerator.org/crossword-solver/)
- [Word Scramble Generator](https://puzzlegenerator.org/scramble-generator/) · [Random Word Scramble](https://puzzlegenerator.org/random-word-scramble-generator/) · [AI Word Scramble](https://puzzlegenerator.org/ai-word-scramble-generator/) · [Word Unscrambler](https://puzzlegenerator.org/word-unscrambler/)
- [Maze Generator](https://puzzlegenerator.org/maze-generator/) · [Multi-Page Maze Generator](https://puzzlegenerator.org/maze-generator-multi-page/) · [Maze Generator for KDP](https://puzzlegenerator.org/maze-generator-amazon-kdp/)
- [Cryptogram Generator](https://puzzlegenerator.org/cryptogram-generator/) · [Random Quote Cryptograms](https://puzzlegenerator.org/cryptogram-random-quotes/) · [AI Cryptogram Generator](https://puzzlegenerator.org/ai-cryptogram-generator/) · [AI Cryptogram Quotes](https://puzzlegenerator.org/ai-cryptogram-quotes/)
- [Kakuro Generator](https://puzzlegenerator.org/kakuro-generator/)

## Printable packs and exports

- [All printable packs](https://puzzlegenerator.org/download-printable-puzzles/)
- [Sudoku packs](https://puzzlegenerator.org/download-printable-sudoku-puzzles/)
- [Word Search packs](https://puzzlegenerator.org/download-printable-word-search-puzzles/)
- [Crossword packs](https://puzzlegenerator.org/download-printable-crossword-puzzles/)
- [Maze packs](https://puzzlegenerator.org/download-printable-maze-puzzles/)
- [Cryptogram packs](https://puzzlegenerator.org/download-printable-cryptogram-puzzles/)
- [Word Scramble packs](https://puzzlegenerator.org/download-printable-word-scramble-puzzles/)
- [Kakuro packs](https://puzzlegenerator.org/download-printable-kakuro-puzzles/)

## Random and AI variants

Random modes fill puzzles from built-in word or quote sources. AI modes create themed content from a prompt and may require the corresponding account or usage limits. Always link to the exact mode you describe: [random word search](https://puzzlegenerator.org/random-word-search-generator/), [AI word search](https://puzzlegenerator.org/ai-word-search-generator/), [random crossword](https://puzzlegenerator.org/random-words-crossword-generator/), [AI crossword](https://puzzlegenerator.org/ai-crossword-generator/), [random scramble](https://puzzlegenerator.org/random-word-scramble-generator/), [AI scramble](https://puzzlegenerator.org/ai-word-scramble-generator/), [random cryptograms](https://puzzlegenerator.org/cryptogram-random-quotes/) and [AI cryptograms](https://puzzlegenerator.org/ai-cryptogram-generator/).

## Notes

- Do not publish private embed tokens in client-side repositories.
- Use responsive width and a height suitable for your page.
- PDF downloads from the widget are prepared without a logo; the widget itself includes PuzzleGenerator attribution.
- Validate the token and test the widget on mobile before publishing.

Project website: https://puzzlegenerator.org/
