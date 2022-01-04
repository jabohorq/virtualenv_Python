# virtualenv_Python
Tool to create isolated python environments.

sudo apt update
sudo apt-get install python3-pip

python3 -m pip install --upgrade pip
pip3 install virtualenv
which virtualenv

Install
$ sudo -H pip install --upgrade virtualenv

Create a virtual environment for a project
# cd project_folder
# virtualenv my_project

Use a specific python interpreter
# virtualenv --python python3 my_project

Activate project
# source my_project/bin/activate

Install packages
# pip install requests
# pip install numpy scipy matplotlib ipython jupyter pandas sympy nose

Create a requirements file
# pip freeze > requirements.txt
Exit
# deactivate


PROJECT MPI4PY
# mkdir mpiProy
# cd mpiProy/
# virtualenv mpiProy
# source mpiProy/bin
#  pip install requests
# pip install numpy scipy matplotlib ipython
# pip install mpi4py
# pip freeze > requirements.txt


