# building-condas

A repo to hold files and instructions related to building conda packages

-----------------------------

## Example to make and load simple conda env

<code> conda create --name testenv pandas </code>

The above creates a conda environment named "testenv" and installs the package pandas into it.

<code> conda activate testenv </code>

The above code loads the environment.

## Example to make a conda env with a specified python version

<code> conda create --name testenv1 python=3.10 </code>

The above code creates an env with python 3.10. This can be checked after loading via the following code.

<code> python --version </code>
