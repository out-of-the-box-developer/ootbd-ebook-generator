# ootbd-ebook-generator
This is a markdown format documents to PDF format generator. It supports emoji, toc generation, and mermaid.

Inspired by @bmf-san [docs-md-to-pdf-example](https://github.com/bmf-san/docs-md-to-pdf-example.git)

# Get Started

## Installation 

First, install dependencies
`npm install`

## Generate PDF

Follow these steps to generate PDF from your markdown files:

1. Place your markdown files in `/md` folder.
2. Generate your PDF `npm run gen-pdf`.

## Generate Table of Content

Follow these steps to generate Table of Content of your markdown files:

1. Place your Markdown in `/md` folder.
2. Generate Table of Content `npm run gen-doctoc`. This command will change your markdown file to add Table of Content.
3. Then generate your PDF `npm run gen-pdf`.