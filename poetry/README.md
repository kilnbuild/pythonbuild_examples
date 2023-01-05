This is an example of using [python.build](https://python.build) with [Poetry](https://github.com/python-poetry/poetry) on an Apple Silicon Mac.

## Usage
```bash
python --version # should show 3.10.x
poetry --version # should show 1.3.1
poetry install # Should install on Apple Silicon, Linux, etc
```

Mac output:
```bash
Installing dependencies from lock file

Package operations: 6 installs, 0 updates, 0 removals

  • Installing six (1.16.0)
  • Installing grpcio (1.47.2)
  • Installing protobuf (3.20.3)
  • Installing grpcio-tools (1.47.2 https://wheels.python.build/grpcio_tools-1.47.2-cp310-cp310-macosx_11_0_arm64.whl)
  • Installing lxml (4.6.5 vendored/lxml-4.6.5-cp310-cp310-macosx_11_0_arm64.whl)
  • Installing toml (0.10.2)
```

## Tested Environment
This has been tested with the following environment:

- Python 3.10.9
- Poetry 1.3.1

## Tested Packages
- [grpcio 1.47.2](https://pypi.org/project/grpcio/1.47.2/) (released September 2022)
- [grpcio-tools 1.47.2](https://pypi.org/project/grpcio-tools/1.47.2/) (released September 2022)
- [lxml 4.6.5](https://pypi.org/project/lxml/4.6.5/) (released December 2021).

Please see the `pyproject.toml` file for the full example and explanation.