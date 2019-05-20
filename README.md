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

## Why you should use virtual environments
<pre>
Virtual environments:
  - keep your project dependencies isolated
  - help you avoid version conflicts between packages and different version of the Python runtime

As a best practice:
  - use virtual environments for all of your Python projects in order to store their dependencies
  - and be mindful of what packages you install in a non-virtual environment as such package installs
    will go into the global environment
</pre>


## Useful pip commands
<pre>
pip3 --version
pip3 --help
pip3 list [--outdated]
pip3 show [name]
</pre>


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

## Installing packages with version specifiers
<pre>
Examples:
  $ pip3 install requests==2.1.4 (specific version)
  $ pip3 install requests>=2,<3  (latest 2.x.x version)
  $ pip3 install requests~=2.1.4 (any 2.1.X version >= 2.1.4)
</pre>

## Installing packages from Git (and other sources)
<pre>
$ pip3 install git+https://github.com/user/repo.git@branch

More examples:
  - $ pip3 install git+https://github.com/davidclin/cloudcustodian-policies.git@master   (install from branch)
  - $ pip3 install git+https://github.com/davidclin/cloudcustodian-policies.git@3adef5ca (install from hash)
  - $ pip3 install git+https://github.com/davidclin/cloudcustodian-policies.git@v1.10.2  (install from tag/release)
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

