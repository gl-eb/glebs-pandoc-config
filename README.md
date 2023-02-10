# Gleb's Pandoc Configuration

Currently this repository only contains a Pandoc Defaults file I use to convert documents to pdf. To use it run the following command within the folder containing both the input and the defaults files:

```bash
pandoc <input_file> -o <output_file> --defaults=latex.yaml
```