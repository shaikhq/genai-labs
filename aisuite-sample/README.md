1. Install `uv` for Python 3.12
```shell
python3.12 -m pip install uv
```

2. Create a Python virtual environment
```shell
uv venv --python=python3.12
```

3. Activate the virtual environment
```shell
source .venv/bin/activate
```

4. Install packages from requirements.txt
```shell
uv pip install -r requirements.txt
```