# debbugs

A Python client for the Debbugs bug tracking system.

[Debbugs](https://wiki.debian.org/Debbugs) is the bug tracking system used by the Debian project and several other open source projects. This library provides a clean Python interface to interact with Debbugs instances via their SOAP API.

## Installation

```bash
pip install debbugs
```

## Requirements

- Python 3.10 or later

## Usage

```bash
debbugs
```

## Development

Clone the repository and install development dependencies:

```bash
git clone https://github.com/conao3/python-debbugs.git
cd python-debbugs
pip install -e ".[dev]"
```

Run the tests:

```bash
pytest
```

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.
