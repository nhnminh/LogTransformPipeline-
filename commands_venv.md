# Create virtual environment 
# Under the current project
python3 -m venv env

# Activate virtual environment 
source env/bin/activate

# Confirm if we are in the virtual env 
which python
.../env/bin/python


# Installing from requirement files
pip install -r requirements.txt


# Export list of dependencies
pip freeze
-------------------------------------
# Leaving virtual env 
deactivate

https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/#creating-a-virtual-environment

https://opensource.com/article/18/2/why-python-devs-should-use-pipenv