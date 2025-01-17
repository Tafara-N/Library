# Converting files from (.epub and .chm) to .pdf

## Table of Content
- [Author](#author)
- [From `.chm` to `.pdf`](#converting-from-chm-to-pdf)
- [From `.epub` to `.pdf`](#converting-from-epub-to-pdf)
- [Opening and Reading Files](#opening-and-reading-files)


## Opening and Reading Files

**`.chm` files**

```bash
sudo apt-get update
sudo apt install xchm
```

**`.epub` files**

```bash
sudo snap install okular
```
___

## Conversion

### Converting from `.chm` to `.pdf`

1. **Using a free online tool [Zamzar](https://www.zamzar.com/convert/chm-to-pdf/)**

- Upload the `file.chm` file.
- File gets converted to `pdf`, or an extension of your choice.
- Download the converted `file.pdf` file.
- All done

2. **Using calibre**

```bash
sudo apt-get update
sudo apt-get install calibre
ebook-convert file.chm file.pdf
```

### Converting from `.epub` to `.pdf`

1. **Using Okular**

> **Have `Okular` installed**

```bash
sudo snap install okular
```

- Select the `file.epub` you want and open it with `Okular`
- Once opened, follow the below steps:

![Converting from `.epub` to `.pdf`](../images/okular_conversion.png)


2. **Using calibre**

```bash
sudo apt-get update
sudo apt-get install calibre
ebook-convert file.epub file.pdf
```

## Author

**Tafara Nyamhunga  - [Github](https://github.com/tafara-n) / [Twitter](https://twitter.com/tafaranyamhunga)**
