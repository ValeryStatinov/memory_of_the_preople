# Parsing memory of the people
https://pamyat-naroda.ru/

## Installation
### With virtualenv (preferred)
Assume that you have python3 and jupyter notebook installed
```bash
python3 -m venv venv # create virtual environment; it means that all further actions will be done in isolated python, not in system one

source venv/bin/activate # activate venv

pip install -r requirements.txt # install dependencies

python -m ipykernel install --user --name venv --display-name 'Playground venv' # create new kernel for jupyter, that will use our venv

jupyter notebook # launch notebook
```

:warning: In the top menu select Kernel -> Choose kernel -> Playground venv

After you are done with this project type
```bash
jupyter kernelspec uninstall venv
```
to delete kernel

### Without venv
```bash
pip3 install -r requirements.txt
jupyter notebook
```
