### Update all packages after a clean install.

`conda update -all`

### Installs a package with the corresponding name.

To install more than one package seperate the pack names with a space (numpy pandas, scipy)

To install package with a specific version write it as follows: python=3

`conda install package_name`

### Creates a new enironment

`n` is an environment **name** flag

`conda create -n env_name package_names`

### Lists all packages in a given environment

`conda list`

### Lists all environments

`conda env list`

### Activates the environment with the name env_name

`activate env_name` for Windows

`source activate env_name` for OSX/Linux

### Install Jupyter notebook in Anaconda
`conda install jupyter notebook`
