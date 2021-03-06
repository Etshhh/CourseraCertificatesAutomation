# CourseraCertificatesAutomation

This repo is a project for automating downloading your Coursera Certificates

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the requirements.

* *Make sure you're in the package directory before running the following command.*  
* *It may be* ```pip3``` *for you, this depends on how you aliased your python version.*

```bash
pip install -r requirements.txt
```

## Before Running
For the script to be able to access your account, add a ```confidentials.py``` file in the project directory, and have it contain *three* variables.
```python
email = 'abc@mail.com'
password = 'password'
download_path = r"D:\DP\certs"
```

## Usage
*It may be* ```python3``` *for you, this depends on how you aliased your python version.*
```bash
python gui.py
```
The script will pause after signing in for the user *(you)* to solve the recaptcha, if one exists, and then press enter back in the terminal you ran the script in for the it to continue.

## Demo
Here is a screen recording of the script while running. [Video link](https://drive.google.com/file/d/1EowJhiofUwAUa12cAuh_lJWCZLtYrC80/view?usp=sharing)

## License
[MIT](https://choosealicense.com/licenses/mit/)
