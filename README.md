# python-resources
Python Resources

# IDEs
[Pycharm](https://www.jetbrains.com/pycharm/)

# Plug-ins and Other Nifty Tools
[jedi-vim](https://github.com/davidclin/jedi-vim)
<br>
[botostubs](https://github.com/davidclin/botostubs)

# Tutorials
[Learn Python with Socratica (YouTube)](https://www.youtube.com/watch?v=bY6m6_IIN94&list=PLi01XoE8jYohWFPpC17Z-wWhPOSuh8Er-) 
<br>
[The Python Tutorial](https://docs.python.org/3.7/tutorial/index.html) 
<br>
[Real Python Tutorial](https://realpython.com/)
<br>
[The Hitchhiker's Guide to Python](https://docs.python-guide.org/)

# Cheatsheets
[Pythonsheeets](https://www.pythonsheets.com/)

# Pycharm Tips
## Change code font size using Mouse wheel
    cntl + alt + s : General --> Change font size (Zoom) with Ctrl+Mouse Wheel <br>
## Use Interactive Python
    Tools --> Python console <br>
    
# Managing Python Dependicies
Use virtual environments

## Useful pip commands
pip3 --version
pip3 --help
pip3 list

## Installing pip
<pre>
Linux (Debian/Ubuntu)
$ sudo apt update
$ sudp apt install python-pip

macOS & Windows
Download https://bootstrap.pypa.io/get-pip.py
$ python get-pip.py
</pre>

## Python Packaging
[Click here](packaging.python.org/installing)

## Updating pip to the latest version
<pre>
Linux (Debian/Ubuntu)
$ sudo apt update && sudo apt upgrade python-pip

macOS
$ sudo pip3 install --upgrade pip setuptools

Windows:
C:\>pip3 install --upgrade pip setuptools
</pre>


## Searching for packages on PyPI
<pre>
Option 1 (Preferred): PyPI website -> pypi.python.org
Option 2 $ pip3 search [name] 
</pre>


## Installing packages with pip
<pre>
$ pip3 install [name]
</pre>


## Identifying & Updating Outdated Packages
<pre>
$ pip3 list --outdated
$ pip3 install --upgrade [name]
</pre>


## Uninstalling packages
<pre>
$ pip3 uninstall [name] (Note: pip uninstall DOES NOT uninstall secondary dependencies)
</pre>

