# Development envvironment setup

```sh
python3 -m venv qip-pass-export/venv
cd qip-pass-export
source venv/bin/activate
pip install --upgrade pip
pip install --editable '.[dev]'
```

# Build

```sh
hatch build
```

# Linting

## Apply standardized formatting

```sh
hatch run lint:fmt
```

## Only perform checks (standardized and more)

```sh
hatch run lint:check
```
