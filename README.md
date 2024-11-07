# Usage (VSCode)

1. Create Python Virtual Environment folder inside the `tm-30-playground folder`:

```
cd tm-30-playground

python3 -m venv .venv
```

2. Activate the environment:

```
source .venv/bin/activate
```

3. Install Python dependencies:

```
pip install -r requirements.txt
```

_When the virtual environment is active the pip installs packages inside it's folder (.venv in our case) instead of insatlling it globally on the system_


4. Install Jupyter notebook extension in VSCode:

https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter

5. Open project folder in VSCode.

6. Open `tm30.ipynb` file and choose `.venv` as a kernel (a dropdown at the top right corner of the current file window).

    _This will let VSCode and Jupyter extension know where you installed python packages._

7. `Run all` button (at the top of the current file window).

    _This will execute all the code in the notebook and update the output (the plot)_
