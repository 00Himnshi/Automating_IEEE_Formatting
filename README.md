# Automating IEEE Formatting

## Introduction

This project aims to automate the process of formatting research papers according to IEEE guidelines using Python. When preparing manuscripts for IEEE journals or conferences, authors often face the challenge of ensuring their documents adhere to strict formatting requirements, such as specific margins, heading styles, font sizes, and paragraph spacing. Manually formatting long documents can be tedious and error-prone.

This Python script solves that problem by automatically converting plain text into a properly formatted IEEE-style document. It reads an input text file, detects section headings (main, sub, and sub-subsections), and applies the correct formatting for each, including title pages, author names, affiliations, and abstracts.

## Key Features

- **Automatic Title Page**: Creates a professional title page with the paper's title, authors, affiliations, and an abstract.
- **Heading Formatting**: Automatically identifies and formats main sections, subsections, and sub-subsections according to IEEE style.
- **Body Text**: Ensures consistent font size, line spacing, and paragraph formatting for the document body.
- **IEEE-compliant Margins**: Sets the correct margins (1 inch on all sides) for IEEE papers.

## How It Works

1. The script reads an input `.txt` file containing the content of your paper.
2. It identifies different levels of headings (main sections, subsections, and sub-subsections).
3. It applies the correct IEEE formatting (font size, style, alignment) for the title page, headings, and body text.
4. The formatted document is saved as a `.docx` file.

## How to Run

1. Install Python and the `python-docx` library.
2. Provide a `.txt` file with your paper's content.
3. Run the script to generate an IEEE-formatted DOCX file.
