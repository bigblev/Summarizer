# Moby-Dick Vertical Chapter Summary Process

Use this process whenever James requests a new Moby-Dick chapter summary.

## Canonical template
- Repository: bigblev/Summarizer
- Branch: main
- Template file: MOBY DICK vertical episode summary example.md
- Match the template’s structure exactly:
  - **MOBY DICK** title block
  - Or The Vertical Whale subtitle
  - **Chapter/Episode:** Chapter <number>: <TITLE IN CAPS>
  - **SUMMARY**
  - **KEY QUOTES**
  - **KEY THEMES**
  - **KEY EVENTS**
  - **CINEMATIC IMAGES**
  - **CHARACTERS**
  - **LOCATIONS**

## Source text
- Source chapter text from Project Gutenberg’s public-domain Moby-Dick text:
  https://www.gutenberg.org/cache/epub/2701/pg2701.txt

## Output rules
- Save each result as a new Markdown file named by chapter number and title.
- Use plain Markdown with bold section labels, no # headings inside the chapter summary file.
- Keep CHARACTERS and LOCATIONS as plain hard-line-break lists, not bullets.
- Use one memorable verbatim quote in KEY QUOTES.
- Keep prose sections concise, present-tense, and cinematic.

## Batch workflow
- For multiple requested chapters, create one Markdown file per chapter.
- Package the files into a single zip archive for download or email.
- If emailing, request approval of the final email draft before sending.
