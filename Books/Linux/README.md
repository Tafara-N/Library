# A collection of Linux books

## Table of Content

* [Author](#author)
* [Books](#books)
* [Tips](#tips)

## Books

```bash
📦Books
 ┗ 📂Linux
    ┣ 📜A Practical Guide to Linux Commands.pdf
    ┣ 📜CompTIA Linux+ Powered by Linux Professional Institute Study Guide.pdf
    ┣ 📜CoreOS in Action: Running Applications on Container Linux.pdf
    ┣ 📜How Linux Works.pdf
    ┣ 📜Linux Bible.pdf
    ┣ 📜Linux Command Line and Shell Scripting Bible.pdf
    ┣ 📜Linux Smart Homes For Dummies.pdf
    ┣ 📜Linux for Beginners.epub
    ┣ 📜Pro Linux System Administration.pdf
    ┣ 📜README.md
    ┣ 📜Running Linux.pdf
    ┣ 📜The Book of XEN.pdf
    ┣ 📜The Linux Command Line.pdf
    ┣ 📜The Linux Programming Interface: A Linux and UNIX System Programming.pdf
    ┣ 📜Understanding The Linux Kernel.pdf
    ┗ 📜Using Samba.pdf
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
