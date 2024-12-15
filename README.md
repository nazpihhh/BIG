# BIG
New era is coming
# Мій проект

Це мій новий проект, який займається автоматизацією задач. Він дозволяє легко виконувати певні операції через командний рядок.

## Як встановити

1. Клонуйте репозиторій:
   ```bash
   git clone https://github.com/ваш_акаунт/big.git
   pip install -r requirements.txt
# main.py
print("Hello, World!")
/my-repo
    /src
        main.py
    /docs
        README.md
    requirements.txt
    .gitignore
    LICENSE
name: Python package

on: [push]

jobs:
  test:
    runs-on: ubuntu-latest

    steps:
      - name: Check out code
        uses: actions/checkout@v2
      - name: Set up Python
        uses: actions/setup-python@v2
        with:
          python-version: '3.8'
      - name: Install dependencies
        run: |
          python -m pip install --upgrade pip
          pip install -r requirements.txt
      - name: Run tests
        run: |
          pytest
