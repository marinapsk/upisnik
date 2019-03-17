# Setting up development environment

1. Install PostgreSQL
  For installation go to https://www.enterprisedb.com/downloads/postgres-postgresql-downloads and select windows x32 or windows x64 version of the database depending on your OS.
  During setup change the Default locale to Croatian, Croatia.
2. Install Python.
  Make sure your Python runs from command line by executing this in command console `python --version`. If Windows can't find Python you need to add location of Python.exe to system PATH environment variable.
3. Make sure you can run `pip` command line tool.
  Run `pip --version` from command line. If pip isn’t already installed try to install it with `python -m ensurepip --default-pip`.
4. Ensure pip, setuptools, and wheel are up to date by running this from the command line.
  `python -m pip install --upgrade pip setuptools wheel`.
5. Install SQLAlchemy.
  Open command line and run `pip install SQLAlchemy==1.3.1`.