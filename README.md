# jupyter-test

## Setup Environment

### Conda

```sh
conda env create -f environment.yml
conda activate jupyter-test
```

### PyPI

```sh
pip install -r requirements.txt
```

## Run Tests

```sh
python -m pytest --nbmake
```

### Run Tests in Parallel

```sh
python -m pytest --nbmake -n=auto
```
