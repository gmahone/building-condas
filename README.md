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

## How to see what conda envs are available

<code> conda info --envs </code>

The above code gives a list of conda envs, with an asterisk by the active one.

## Creating a conda environment from a environment.yml file

<code> conda env create -f environment.yml </code>

An example of a simple environment.yml file is available in this repo.
