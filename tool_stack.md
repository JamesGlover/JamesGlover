# Tool Stack

Quick notes on some tools and plugins I've found useful

## Editors

### Sublime

My go-to editor for many years, taking over from Text Mate. Nice and fast.

### VS Code

I started playing around with VS Code at the start of lock-down due to its excellent [code-collaboration tools](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare). Despite being slower than Sublime, its become my main editor, thanks to some excellent extensions.

#### VS Code extensions

These are some of the extensions I've found useful.

[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
Excellent git history integration, providing quick access to commit messages, history and comparisons. The ability to
click back and forward through code history is fantastic.

[Code Template Tool](https://marketplace.visualstudio.com/items?itemName=yuanhjty.code-template-tool)
Allows you to set-up templates for files, or whole collections of files. Templates
can take a number of parameters, and happily convert between various case formats.
Not perfect, I'd love to be able to, say, select a model and automatically generate
the specs for it, but still very useful. I keep my [templates here](https://github.com/JamesGlover/template_collectio).

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
