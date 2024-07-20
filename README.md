## AI Intergrated Discord Bot

LangChain: A Framework to build controllable agentic workflows.
PostgresSQL: Database for storing and retrieving of data
    SQL Model:To create SQl database with Python
PyCord: Python Package to create a discord Bot

## WorkFlow

### Creating a Discord Bot

Link: https://discord.com/developers/applications
1. Login to your account to proceed with bot creation. 
2. Once the bot name is finalised, Go to the "Bot" page to provide permission
3. Administrator permission, gives bot all the intents in a discord server.
4. Select on required Intents that the bot should have.
5. Permission for the bots like... Access the messages/ Access some channels in the server is given from the OAuth tab.
6. Once all the changes are done, copy the URL and use it to add it to the corresponding server.


### Set Up Directory and Dependency
1. To create a Python virtual Environment
```console
$ python -m venv <virtual env name>
```
2. To activate the virtual environment,
```console
$ venv/Scripts/activate.ps1 (for powershell)
$ venv/Scripts/activate.bat (for cmd)
```

3. Install all the dependencies
```console
$ pip install langchain
$ pip install "py-cord[speed]"
$ pip install sqlmodel
$ pip install alembic
```
