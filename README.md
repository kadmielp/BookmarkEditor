# Bookmark File Editor

A simple, dependency-free HTML app for editing bookmark files exported from a browser.

The app runs entirely in your browser from a single `index.html` file. It does not upload bookmark data anywhere and does not require installation, a build step, or a server.

## Features

- Open browser-exported bookmark `.html` / `.htm` files
- Browse bookmark folders in a tree view
- Search bookmark titles and URLs
- Edit bookmark titles, URLs, and dates
- Rename folders
- Add folders and bookmarks
- Move items between folders
- Reorder items inside a folder
- Sort a folder alphabetically, with folders first
- Delete selected bookmarks or folders
- Export an edited Netscape-compatible bookmark HTML file

## Usage

1. Open `index.html` in a web browser.
2. Click **Open bookmark file**.
3. Select a bookmark export file from Chrome, Edge, Firefox, Brave, or another browser that exports Netscape bookmark HTML.
4. Edit, organize, add, delete, or sort bookmarks.
5. Click **Export HTML** to download the edited bookmark file.
6. Import the exported file back into your browser if desired.

## Browser Export Notes

Most browsers export bookmarks as an HTML file using the Netscape bookmark format. This app reads and writes that format so the exported file can be imported back into common browsers.

## Privacy

Bookmark files are processed locally in the browser tab. No network request is required to edit a file when opening `index.html` directly.

## Development

There is no build pipeline. Edit `index.html` directly and reload the browser.

For optional local preview during development:

```bash
python -m http.server 4173 --bind 127.0.0.1
```

Then open:

```text
http://127.0.0.1:4173/index.html
```
