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

5. rename `.env-sample` to `.env` and populate the API key and metadata from the target ai platforms. i.e., necessary values as follows need to be filled in. 
   ```
   # WatsonX
WATSONX_SERVICE_URL=
WATSONX_API_KEY=
WATSONX_PROJECT_ID=

#OpenAI
OPENAI_API_KEY=

# AWS SDK credentials
AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_REGION=
```

