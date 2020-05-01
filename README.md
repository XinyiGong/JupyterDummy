# Test Jupyter Notebook on GitHub through Binder Hub using Conda environment with environment.yml
A Binder-compatible repo with an environment.yml file.

## Notes
The environment.yml file should list all Python libraries on which your notebooks depend, specified as though they were created using the following conda commands:

> source activate example-environment

> conda env export --no-builds -f environment.yml
