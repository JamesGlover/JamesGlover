# Tool Stack

Quick notes on some tools and plugins I've found useful

## Editors

### Sublime

My go-to editor for many years, taking over from Text Mate. Nice and fast.

### VS Code

I started playing around with VS Code at the start of lock-down due to its excellent [code-collaboration tools](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare). Despite being less performant than Sublime, its become my main editor, thanks to some excellent plugins.

## CLI

### Bat
[Bat](https://github.com/sharkdp/bat) is a super-charged version of cat, with syntax highlighting, git integration and automatic pagination.

For example `bat --line-range 0:4 *.csv` will render the first 4 lines of every
csv file, as so:
```
───────┬────────────────────────────────────────────────────────────────────────
       │ File: file_a.csv
───────┼────────────────────────────────────────────────────────────────────────
   1   │ Header a, Header b
   2   │ 1,2
   3   │ 1,3
   4   │ 1,4
───────┴────────────────────────────────────────────────────────────────────────
───────┬────────────────────────────────────────────────────────────────────────
       │ File: file_b.csv
───────┼────────────────────────────────────────────────────────────────────────
   1   │ Header a, Header b
   2   │ 3,5
   3   │ 3,6
   4   │ 3,7
───────┴────────────────────────────────────────────────────────────────────────
```
