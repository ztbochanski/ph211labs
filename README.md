# Physics 211

This repository contains all of the work, labs, and knowledge learned in [Bruce Emerson's](http://coccweb.cocc.edu/bemerson/PhysicsGlobal/Courses/PH211/PH211.html) physics 211 course. 

## JupyterLab Installation and Setup

### Install
*"To remember how to set up jupyterlab"*  

Here is the [JupyterLab Documentation](https://jupyterlab.readthedocs.io/en/stable/)  

Homebrew as a package manager: ```brew install jupyterlab``` in the terminal adds the jupyterlab package to local dev tools.  

Here's the specific [homebrew formulae](https://formulae.brew.sh/formula/jupyterlab)  

###  Virtual development environment
A good reason to set up a *virtual environment* is so all the development takes place within one isolated directory, and an isolated copy of python.

1. First, open a terminal window and `pip install virtualenv` a popular python tool that creates isolated python environments [docs](https://virtualenv.pypa.io/en/latest/index.html).  

2. Now create a virtual environment using the command `virtualenv <myname>`. In this case the name is *jlabenv*. It is the jupyter lab environment for all of physics 211.  

3. Once it is created it can be activated with `source jlabenv/bin/activate`  

4. Next, install `pip install --user ipykernel` which provides the IPython kernel for Jupyter.  

5. Finally, `python -m ipykernel install --user --name=jlabenv` plugs in the environment into Jupyter! It should tell the path were the environment was added to Jupyter. 
   
6. Try `jupyter kernelspec list` to see all the environments that are plugged into Jupyterlab. 

Nice, a virtual environment with python has been configured and is ready to go for all of physics class, stuff breaking will be nicely contained!  

### Launch in Browser

1. To get started in a browser: `CMD + Space`, type `terminal`

2. Inside terminal run: `jupyter-lab`

### Launch in Visual Studio Code

Why would one want vscode? ...better IDE tools, and familiarity with commands etc.

1. Download [Visual Studio Code](https://code.visualstudio.com)

2. Open `.ipynb` files and edit.




