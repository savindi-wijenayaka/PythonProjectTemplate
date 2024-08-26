# PythonProjectTemplate
The project description is here

## Setting up a dedicated environment
1. Create conda environment.
```bash
conda create -n <ENV-NAME> python=3.11 -y
```

2. Install prerequisites
```bash
pip install -r requirements.txt
```

3. Check if the pre-commit hook is working as expected
```bash
pre-commit run --all-files
```

## Code formatting, linting and complexity analysis

