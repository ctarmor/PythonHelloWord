# PythonHelloWord
Practice Python


https://code.visualstudio.com/docs/python/python-tutorial#_prerequisites


https://code.visualstudio.com/docs/python/environments#_global-virtual-and-conda-environments
Virtual env Setup

source /Users/carlosalvarez/MyDevelopment/PythonHelloWord/.venv/bin/activate

carlosalvarez@carloss-mbp PythonHelloWord % source /Users/carlosalvarez/MyDevelopment/PythonHelloWord/.venv/bin/activate
(.venv) carlosalvarez@carloss-mbp PythonHelloWord % /Users/carlosalvarez/MyDevelopment/PythonHelloWord/.venv/bin/python /Users/carlosalvarez/MyDevelopment/PythonHelloWord/standardplot.py

Traceback (most recent call last):
  File "/Users/carlosalvarez/MyDevelopment/PythonHelloWord/standardplot.py", line 1, in <module>
    import matplotlib.pyplot as plt

ModuleNotFoundError: No module named 'matplotlib'

(.venv) carlosalvarez@carloss-mbp PythonHelloWord % pip freeze > requirements.txt
(.venv) carlosalvarez@carloss-mbp PythonHelloWord % https://code.visualstudio.com/docs/python/environments#_global-virtual-and-conda-environmentshttps://code.visualstudio.com/docs/python/environments#_global-virtual-and-conda-environments


install: 
python3 -m pip install matplotlib

