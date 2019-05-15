# jupyter_githooks
Pre-commit githooks to prevent committing Jupyter notebooks with executed output

## Installation
```
touch .git/hooks/pre-commit
curl https://raw.githubusercontent.com/isaacanthony/jupyter_githooks/master/pre-commit >> .git/hooks/pre-commit
chmod +x .git/hooks/pre-commit
```
