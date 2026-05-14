# colors

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

This repository provides a dataset of the 140 named web colors specified in the [CSS Color Module Level 3](https://www.w3.org/TR/css-color-3/). The data is available in CSV, JSON, and CBOR formats.

## Available Formats

The color data is provided in the following files:

- [`webcolor.csv`](webcolor.csv)
- [`webcolor.json`](webcolor.json)
- [`webcolor.cbor`](webcolor.cbor)

## Data Structure

Each color entry consists of a `name` (string) and its corresponding hexadecimal `color` code (string).

**Example (JSON):**
```json
[
  {
    "name": "aliceblue",
    "color": "#f0f8ff"
  },
  {
    "name": "antiquewhite",
    "color": "#faebd7"
  }
]
```

## License

This project is licensed under the MIT License.