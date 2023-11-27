# template_poetry_docker
myTemplate for poetry &amp; dockerfile


## Install Poetry
```python
# WSL, Linux
curl -sSL https://install.python-poetry.org | python3 -

# Powershell in Windows
(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | python -
```


## Poetry local folder path
- `~/.local/share/pypoetry` on Linux/Unix.
- `%APPDATA%\pypoetry` on Windows.

## installer set Poetry local folder path as
- `$HOME/.local/bin` on Unix.
- `%APPDATA%\Python\Scripts` on Windows.


## update poetry
```
poetry self update
```
