


## EgeaML
Course-specific module, called **egeaML**. <br>
Please, clone on your local machine this repo, as follows:
```bash
git clone https://github.com/aofphy/APML2022.git
```
To install it into your local env, I recommend to create a virtualenv where you add the necessary requirements, running this command from your favourite terminal emulator:
```bash
pip install -r requirements.txt
pip install git+https://github.com/aofphy/APML2022.git
```

If, instead, you use the Anaconda system:
```
conda install --file requirements.txt
conda install git+https://github.com/aofphy/APML2022.git
```
If you have Python3 already installed in your local environment, you can run:
```bash
python3 -m pip install --upgrade pip
python3 -m pip install git+https://github.com/aofphy/APML2022.git
```
To use it inside your Python3 environment, you should initialise the class as follows:
```python
import egeaML.egeaML as eml
```
or alternatively
```python
from egeaML.egeaML import *
from egeaML.egeaML import DataIngestion
```

# APML2022
