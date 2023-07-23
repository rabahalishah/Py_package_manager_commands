# About: Py_package_manager_commands
This repo contains the most frequently used Python package manager commands and some other commands related to python packages.

# 01 Conda Commands:
```bash
conda create -n my-env
```
```bash
conda activate my-env
```
```bash
conda install numpy
```
```bash
conda list
```
```bash
conda install --file filename
```
```bash
. Scripts/activate //(To activate venv created by pip)
```
```bash
conda create --prefix /tmp/test-env python=2.7 // (creating venv in specific folder)
```

# 02 Pip Commands
### PIP commands
```bash
pip show module_name (to check whether the module is installed or not)
```
```bash
pip list (to check all installed modules)
```
```bash
pip module_name --version  (to check the version)
```
```bash
python -m venv venv_folder_name (to create virtual env)
```
```bash
. path/active (to activate the venv)
```
```bash
pip install module_name
```
```bash
pip install module_name==version (to install the specific version of module)
```
```bash
pip freeze > requirements.txt
```
```bash
You can exit from the virtualenv using exit command, or by pressing Ctrl+d.
```
```bash
pip3 freeze > requirements.txt  (to create requirement.txt file)
```

```bash
pip install jupyterthemes(for installing jupyter themes)
```
```bash
python -m pip install --upgrade jupyterthemes (for upgrading jupyter themes)
```
```bash
jt -t <theme-name>
```

### Available themes:
- onedork
- grade3
- oceans16
- chesterish
- monokai
- solarizedl
- solarizedd

**my fav**
```bash
jt -t monokai -f fira -fs 10 -nf ptsans -nfs 11 -N -kl -cursw 2 -cursc r -cellw 95% -T
```
### Python Creating virtual environment

# how to create a virtual environment
```bash
//syntax :
python -m venv c:\path\venv
```
then restart the terminal 
then type: 
```bash
pip install package name
```





