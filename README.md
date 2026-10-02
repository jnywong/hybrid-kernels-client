Example project using jupyterlab-hybrid-kernels PyPI package.

# Requirements

```bash
pip install jupyterlab-hybrid-kernels jupyterlab jupyterlite-core jupyterlite-pyodide-kernel
```

# To deploy

```bash
jupyter lite build --output-dir dist
jupyter lab --config jupyter_server_config.py
```
