Conda (and Mamba) come with a feature for setting environment variables. However, the commands are cumbersome and there is no easy way to set/unset many variables at once. This CLI tool simplifies the command syntax and allows loading variables from file (i.e. .env)   

### Install
```bash
pip install convars
```

### Usage
```
Usage: convars [OPTIONS] COMMAND [ARGS]...

Options:
  --help  Show this message and exit.

Commands:
  clear   Clear all environment variables from the active environment.
  load    Add environment variables from a file to the active environment.
  set     Set an environment variable in the active environment.
  show    Show environment variables in the active environment.
  unload  Remove environment variables listed in file from the active environment.
  unset   Remove an environment variable from the active environment.
```
