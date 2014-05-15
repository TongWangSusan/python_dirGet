python_dirGet
=============
#get the directory of a file
from config import THIS_ROOT
print THIS_ROOT
#in config.py(in the same directory)
THIS_ROOT = os.path.abspath(os.path.dirname(__file__))
