# Markdown Cheatsheet

## Headings

- #, ##, ###, ####
- Use comment `<!-- title: Your Title -->` to specify a title of the exported HTML.

## Lists, indents

- Use the - for lists
- Use the > for indent

## Tables

- Use | and -
- Need at least 3 ---
- Left Alignment :---
- Center :---:
- Right Alignment ---:
- Pipes on either side

## Task lists

- Need to have list with the - and then [ ] or [x]

- [ ] Eat breakfast
- [ ] Go swim
- [x] Watch a movie

## Hyperlinks

- \[this link](#1.1-Next-Item)
- The # is a single # and has nothing to do with the heading #,##,###,####
- On the receiving side, it needs to be any kind of a heading
- If you want to receive to a bulleted item, the place a #### inside the -

## Command Pallete

- Call it up by Markdown
- Can export to HTML
- Automatically create a TOC
- Section numbers add/remove

## Keyboard shortcuts

| Key                  | Command                      |
| -------------------- | ---------------------------- |
| Ctrl/Cmd + B         | Toggle bold                  |
| Ctrl/Cmd + I         | Toggle italic                |
| Ctrl/Cmd + Shift + ] | Toggle heading (uplevel)     |
| Ctrl/Cmd + Shift + [ | Toggle heading (downlevel)   |
| Ctrl/Cmd + M         | Toggle math environment      |
| Alt + C              | Check/Uncheck task list item |
| Alt + Shift F        | Format Table                 |
| Ctrl/Cmd + Shift + V | Toggle preview               |
| Ctrl/Cmd + K V       | Toggle preview to side       |

## Math (Github)

- In-line delimitter use \$\` in front, \`\$ back
- $y = 3*x + 12$
- Block delimitter use $ in front / back
- Or block delimitters \```math \```
