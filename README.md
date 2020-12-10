# myPySummary

Console tool which reads long texts from `stdin` and outputs a summary of five sentences to `stdout`.

Example usage:

```bash
cat document.txt | python summarize.py
```

The example `document.txt` contains a copy of `The Great Gatsby` by John Fitzgerald (public domain)
and with the example usage, it will output the five most important sentences (as considered by the AI).

## Installation

A virtualenv is recommended:

```bash
python3 -m venv env
source env/bin/activate
```

Install `pysummarization`:

```bash
pip install -r requirements.txt
```
