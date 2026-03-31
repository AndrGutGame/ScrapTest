# ScrapTest

This repository contains simple static pages for testing `changedetection.io`.

## Files

- `index.html` - page for watching visible text and an inline code block
- `page-source.html` - page for watching source code and exact HTML fragments

## Suggested watch targets

- Watch the full page text on `index.html`
- Watch the `#status-text` and `#price-text` sections on `index.html`
- Watch the HTML source or code fragment on `page-source.html`

## Test notes

Change any of the visible text or code snippets, commit the update, then confirm that `changedetection.io` sends a Telegram notification with the diff.
