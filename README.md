# Lab 01 — Introduction to HTML

A first web page built to practise core HTML structure and text formatting.

## Overview

This lab covers the foundations of an HTML document: organising content with
headings, grouping text into paragraphs, and applying inline emphasis. The page
is written in plain HTML with no external libraries, frameworks, or styling, so
the markup itself stays the focus.

## Files

| File | Description |
|------|-------------|
| `index.html` | The web page containing all lab content |
| `README.md` | This document |

## Topics Covered

- **Headings** — `<h1>` for the page title and `<h2>` to separate sections
- **Paragraphs** — `<p>` to group blocks of text
- **Bold** — `<strong>` to mark text with strong importance
- **Italic** — `<em>` to mark emphasised text
- **Nested formatting** — combining `<strong>` and `<em>` on the same text
- **Line breaks** — `<br>` to break a line inside a paragraph

## How to View

Clone the repository and open the page in any web browser:

```bash
git clone git@github.com:dangminh232006/lab01.git
cd lab01
```

Then open `index.html` by double-clicking it, or serve it locally:

```bash
python -m http.server 8000
```

The page is then available at `http://localhost:8000`.

## Notes

`<strong>` and `<em>` are preferred over `<b>` and `<i>`. The visual result is
the same in a browser, but `<strong>` and `<em>` also carry meaning: screen
readers announce the emphasis, while `<b>` and `<i>` only change appearance.

## Author

Bui Dang Minh — Swinburne University
