# bayusianAB_tutorial

## Prerequisites
| software | install(Mac) |
| ---- | ---- |
| python | pyenv install 3.8.6 |
| poetry | curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python |

## poetry configurations
```bash
poetry config virtualenvs.in-project true
```

## Usage
```bash
# install dependencies
poetry install

# run jupyter notebook with the dependencies installed above
poetry run jupyter notebook

```