# Richter's Predictor: Modeling Earthquake Damage

DRIVENDATA Challenge regarding [Modeling Earthquake Damage](https://www.drivendata.org/competitions/57/nepal-earthquake/submissions/).

Can you predict the level of damage to buildings caused by the 2015 Gorkha earthquake in Nepal based on aspects of building location and construction?

The file earthquake.ipynb shows my working.
The data is available from the above link at DRIVENDATA.

## Set up the Environment

This repo contains a requirements.txt file with a list of all the packages and dependecies you will need.

### **`macOS`** type the following commands : 
 Install the virtual environment and the required packages by following commands:
  There are two ways to create and activate a new virtual environment for this repo. You can either use the [requirements](requirements.txt) file and run the following commands.

```BASH
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
  
  *Note: If there are errors during environment setup, try removing the versions from the failing packages in the requirements file.*

### **`WindowsOS`** type the following commands :

 Install the virtual environment and the required packages by following commands:

For `PowerShell` CLI :

```PowerShell
pyenv local 3.11.3
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install -r requirements.txt
```

For `Git-Bash` CLI :
  
```BASH
pyenv local 3.11.3
python -m venv .venv
source .venv/Scripts/activate
pip install --upgrade pip
pip install -r requirements.txt
```

 **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:

   ```Bash
   python.exe -m pip install --upgrade pip
   ```

