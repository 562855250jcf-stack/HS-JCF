# HS-JCF

This repository hosts public files for the WeChat mini program material library.

PDF chunks should be placed under `pdf/`:

- `pdf/fire-requirements.part1.txt`
- `pdf/fire-requirements.part2.txt`
- `pdf/fire-requirements.part3.txt`
- `pdf/fire-requirements.part4.txt`
- `pdf/fire-requirements.part5.txt`

The mini program downloads these chunks, joins the Base64 text, writes the PDF locally, and opens it with `wx.openDocument`.
