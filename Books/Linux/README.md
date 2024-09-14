# A collection of Linux books

## Table of Content

* [Author](#author)
* [Books](#books)
* [Tips](#tips)

## Books

```bash
📦Books
 ┗ 📂Vim
    ┣ 📜Hacking Vim.pdf
    ┣ 📜Learning The Vi And Vim Editors.pdf
    ┣ 📜Vi Improved Book.pdf
    ┗ 📜Vim Like A Pro.pdf
```

## Tips

* Linux
  * https://ops.tips

* Void Linux:
  * http://www.troubleshooters.com/linux/void/voidtips.htm
  * http://www.troubleshooters.com/linux/void/index.htm

* perf stat -r N -d CMD is a great way to measure command running time on Linux.

* Various tip to inspect the system: https://news.ycombinator.com/item?id=16685452

* https://dev.to/brpaz/my-linux-development-environment-of-2018-ch7

* MAN pages: https://news.ycombinator.com/item?id=15775886
* C, Unix, and low-level programming: http://vendu.twodots.nl/wizardcode.html
* Comics: https://jvns.ca/teach-tech-with-cartoons/
* Command-line resources:
  * https://news.ycombinator.com/item?id=15507871
  * https://news.ycombinator.com/item?id=15514589
* Free C books: https://github.com/EbookFoundation/free-programming-books/blob/master/free-programming-books.md

* Regular expressions:
```bash
# === {{CMD}}  path/to/file
# === cat path/to/file | {{CMD}}  no-section
  html-no-section () {
    grep  -Pzo '(?s)(\A.+?)(?=\n\<!--)' $@
  }
# === {{CMD}}   STYLE|FOOT|...   path/to/file
# === cat path/to/file | {{CMD}}   STYLE|FOOT|...
  html-section () {
    section="$1"; shift
    grep  -Pzo '(?s)^\<!--\s+'$section'\s+-->\s?\n\K(.+?)(?=\n<!--|\Z)' $@
  }
```
* Bash: Things I wish I knew before: https://news.ycombinator.com/item?id=16084763

## Author

**Tafara Nyamhunga  - [Github](https://github.com/tafara-n) / [Twitter](https://twitter.com/tafaranyamhunga)**
