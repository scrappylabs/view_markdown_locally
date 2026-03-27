# View Markdown Locally

`markdown_viewer.html` is a single-file local Markdown viewer. You can copy it into any folder and open it directly in a browser.

## What It Does

- Opens and renders a single `.md` file
- Lets you pick a folder and shows all `.md` files in that folder
- Lets you click any listed file to render it
- Supports drag-and-drop for a `.md` file

## How To Use

1. Open `markdown_viewer.html` in a browser.
2. Use one of these options:
   - `Open Markdown File`: open one `.md` file directly
   - `Pick Folder`: choose a folder and list all `.md` files inside it
   - Drag a `.md` file onto the drop area

## Folder Behavior

If you use `Pick Folder`, the viewer will:

- scan the selected folder for `.md` files
- show them in the left sidebar
- let you click any file to render it

If you use only `Open Markdown File`, the viewer will render that file, but it will not automatically know what other Markdown files are in the same folder.

This is a browser security limitation. Browsers do not automatically expose the contents of the HTML file's current directory unless you explicitly grant folder access.

## Browser Notes

- `Pick Folder` works best in Chromium-based browsers
  - Chrome
  - Edge
  - Brave
- In other browsers, direct file open and drag-and-drop may still work, but folder picking may not

## Portability

The viewer is self-contained:

- no installation
- no server
- no external libraries
- no internet connection required

You can move `markdown_viewer.html` into another directory and use it there immediately.
