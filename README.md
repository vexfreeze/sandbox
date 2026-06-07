# Projects

- [notepad](https://vexfreeze.github.io/sandbox/notepad.html)
  * lm code
  * qwen
  * vs code
  * copilot plugin
- [scratchpad](https://vexfreeze.github.io/sandbox/scratchpad.html)
  - opencode
  - big pickle

# Features

## Core
- Full-screen text area with monospace font on a dark background with colored text
- Line number gutter, right-aligned and scroll-synced with the editor
- Padding around editor content

## Tabs
- Multiple tabs with add and close buttons
- Single-click to switch tabs
- Double-click a tab title to rename it inline
- Middle-click a tab to close it
- Right-click context menu on tabs with options to close, restore last closed tab, or clear closed tabs history
- Right-clicking empty tab bar space shows restore/clear options
- Add button stays visible on the right when tabs overflow the bar
- Tabs maintain their natural width and don't compress when the window is narrow
- Double-click empty space in the tab bar to create a new tab

## Scrollbars
- Horizontal scrollbar on the tab bar, styled to match the theme
- Vertical scrollbar on the textarea, styled to match the theme

## Cursor & Selection
- Cursor position and text selection tracked on mouse and keyboard interaction
- Saved on the current tab before switching away
- Restored when returning to a tab
- Restored after page refresh

## Scroll Position
- Editor scroll position saved per tab
- Restored when switching tabs
- Restored after page refresh

## Undo / Redo
- Per-tab undo and redo via keyboard shortcuts
- History is capped to limit storage usage
- Survives page refresh

## Persistence
- All state (tabs, content, history, cursor, scroll, closed tabs) stored in browser local storage
- Survives full page reload
- Limitations: subject to local storage quota limits per origin
