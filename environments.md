#### Why Environments?
--- 
Python applications will often use packages and modules that don’t come as part of the standard library. Applications will sometimes need a specific version of a library.

This means it may not be possible for one Python installation to meet the requirements of every application. For example you might needs tensorflow v1 for a particular project but you might need tensorflow version 2 for another one, then the requirements are in conflict.

The solution for this problem is to create a virtual environment, a self-contained directory tree that contains a Python installation for a particular version of Python, plus a number of additional packages.

Check out https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/ for how to create and use environments in ananconda.

Refer this for more details also https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html
