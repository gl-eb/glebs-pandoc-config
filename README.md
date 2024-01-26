# Gleb's Pandoc Configuration

Currently this repository contains two Pandoc Defaults files I use to convert documents to pdf, either using XeLaTeX or Typst.
To use them run the following command within the folder containing both the input and the defaults files:

```bash
pandoc <input_file> -o <output_file> --defaults=<defaults>.yaml
pandoc input.md -o output.pdf --defaults=latex.yaml
```
