# Assignment 4 – Repository with at least three meaningful commits

```bash
# one-time identity setup
git config --global user.name  "Your Name"
git config --global user.email "you@example.com"

# create the repo
mkdir html-css-assignments && cd html-css-assignments
git init
git branch -M main

# commit 1
echo "# HTML & CSS Assignments" > README.md
git add README.md
git commit -m "docs: add README with project overview"

# commit 2
cp -r /path/to/this/folder/assignments .
git add 01-*.md 02-*.md 03-*.md 04-*.md 05-*.md
git commit -m "docs: add setup & git assignments (1-5)"

# commit 3
git add 06-*.html 07-*.html 08-*.html 09-*.html 10-*.html
git commit -m "feat: add HTML basics assignments (6-10)"

git log --oneline     # shows your history as proof
```

## Good commit-message rules
- Present tense, imperative: *"add navbar"*, not *"added navbar"*.
- Prefix with a type: `feat:`, `fix:`, `docs:`, `style:`, `refactor:`.
- One logical change per commit.

## Suggested history for the whole course
| Commit | Message |
|--------|---------|
| 1 | `docs: add README` |
| 2 | `docs: setup & git assignments (1-5)` |
| 3 | `feat: HTML basics (6-10)` |
| 4 | `feat: links, images, lists (11-15)` |
| 5 | `feat: forms, tables, metadata (16-20)` |
| 6 | `style: CSS fundamentals (21-25)` |
| 7 | `style: box model & positioning (26-30)` |
| 8 | `feat: flexbox layouts (31-35)` |
| 9 | `feat: grid layouts (36-40)` |
| 10 | `feat: responsive landing page (41-45)` |
