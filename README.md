# CALGO to CSV Converter

![Python Version](https://img.shields.io/badge/python-3.11-blue.svg)

`calgo2csv` is a command-line tool designed to convert CALGO data files to CSV format. It offers a straightforward method for processing CALGO formatted data, especially useful for users who handle these files frequently.

## :sparkles: Features

- Convert CALGO files to CSV format either individually or in batches.
- Drag-and-drop functionality on Windows for ease of use.
- No installation required; directly use the pre-built binaries.

## :arrow_down: Getting Started

### Download

Pre-built binaries for `calgo2csv` can be directly downloaded from the GitHub Actions artifacts in the repository. Navigate to the Actions tab of the GitHub repository, select the latest successful build, and download the relevant artifacts for your operating system.

### :computer: Running on Windows

On Windows, you can run `calgo2csv` by simply dragging and dropping your CALGO file onto the executable. Alternatively, you can use the command line as follows:

```bash
calgo2csv_cli calgo_file.txt
```

If you want to convert multiple files at once or specify an output directory, use the command line interface:

```bash
calgo2csv_cli calgo_file1.txt calgo_file2.txt -o /path/to/output
```

### :hammer_and_wrench: Building from Source

If you prefer to compile the tool yourself, refer to the `.github/workflows/ci.yaml` file in the repository for detailed instructions on how to build `calgo2csv` from source.

## :clipboard: Usage

### Command Line Syntax

```plaintext
calgo2csv_cli [-h] [-o OUTPUT] input [input ...]
```

### Arguments

- `input`: Path to the input file(s). If no file is provided, data is read from `stdin`.
- `-o, --output OUTPUT`: Path to the output folder. If not specified, the directory of the input file is used.

### :question: Help

To view help information for the command line interface, use:

```bash
calgo2csv_cli -h
```

---
If you find this project helpful, please consider giving it a ⭐️! Starring this repository helps us to see what projects are most useful to the community and motivates us to constantly improve.