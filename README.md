# About: Py_package_manager_commands
This repo contains the most frequently used Python package manager commands and some other commands related to python packages.

# 01 Conda Commands:
Here are some of the most commonly used Conda commands:

1. **Creating Environments**:
   - ```bash
     conda create --name myenv
     ```: Creates a new environment named `myenv`.
   - ```bash
     conda create --name myenv python=3.8
     ```: Creates a new environment named `myenv` with Python 3.8 installed.
   - ```bash
     conda env list
     ```: Lists all the created environments.

2. **Activating and Deactivating Environments**:
   - ```bash
     conda activate myenv
     ```: Activates the environment named `myenv`.
   - ```bash
     conda deactivate
     ```: Deactivates the current environment.

3. **Managing Packages**:
   - ```bash
     conda install package_name
     ```: Installs a package into the current environment.
   - ```bash
     conda install numpy pandas
     ```: Installs multiple packages at once.
   - ```bash
     conda update package_name
     ```: Updates a package to the latest version.
   - ```bash
     conda remove package_name
     ```: Removes a package from the environment.

4. **Listing Installed Packages**:
   - ```bash
     conda list
     ```: Lists all packages installed in the current environment.

5. **Searching for Packages**:
   - ```bash
     conda search search_term
     ```: Searches for packages containing the specified term.

6. **Environment Management**:
   - ```bash
     conda env export > environment.yaml
     ```: Exports the environment to a YAML file.
   - ```bash
     conda env create -f environment.yaml
     ```: Creates an environment from a YAML file.
   - ```bash
     conda env remove --name myenv
     ```: Removes an environment named `myenv`.

7. **Miscellaneous**:
   - ```bash
     conda info
     ```: Displays information about the current conda installation.
   - ```bash
     conda clean --all
     ```: Cleans unused packages and caches.

These are some of the fundamental Conda commands that are widely used for managing environments and packages.


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
First go inside your virtual environment folder and then run the below script
```bash
. ./Scripts/active (to activate the venv)
```
First go inside your virtual environment folder and then run the below script
```bash
deactivate (press enter, this command is used to deactivate the venv)
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





