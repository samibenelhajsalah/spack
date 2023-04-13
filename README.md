# spack

## Installation
Getting Spack is easy. You can clone it from the github  [repository](https://github.com/spack/spack) using this command:

```git clone -c feature.manyFiles=true https://github.com/spack/spack.git``` 

## Shell support :warning:
>Once you have cloned Spack, we recommend sourcing the appropriate script for your shell:

* **For bash/zsh/sh**
$ . spack/share/spack/setup-env.sh

* **For tcsh/csh**
$ source spack/share/spack/setup-env.csh

* **For fish**
$ . spack/share/spack/setup-env.fish

## Environments Tutorial

* Environment Basics ```TODO``` :hammer:  
* Creating and activating environments

| Use|command |
|---|---|
| create a new environment called myproject |spack env create myproject  |
| activate environment | spack env activate myproject |
| see the environments we’ve created| spack env list |
|shows what is in the current environment/installed packages| spack find |
|check what environment you are in|spack env status|
|leave this environment|spack env deactivate|
|see the path to tclsh|which tclsh|
|install package|spack install tcl|
|uninstall package|spack uninstall package (see [this](https://spack.readthedocs.io/en/latest/basic_usage.html#cmd-spack-uninstall))|
|get detailed information on a particular package|spack info metis|


see the path to tclsh

> **_NOTE:_  :pencil2:**   If you use the -p option for spack env activate, Spack will prepend the environment name to the prompt. This is a handy way to be reminded if and which environment you are in
