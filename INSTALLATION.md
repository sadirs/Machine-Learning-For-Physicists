# Installation

Create an isolated Python environment from the repository root:

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m jupyterlab
```

On macOS or Linux, activate with `source .venv/bin/activate`.

The initial notebooks are templates and do not run teaching experiments yet. TensorFlow/Keras dependencies will be documented and tested when those lessons are implemented. Original 2021 notebooks may require updates for current package APIs.