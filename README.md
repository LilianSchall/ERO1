# ERO1
This is the repository of group 96 for the research project ERO1.

# Setup dev environement:

## On NixOS
To setup the dev environement, simply create a new nix-shell:

```
nix-shell
```

This nix-shell will automatically start a jupyter notebook instance with osmnx and matplotlib as python3 packages.

## On another distro:
You will need the following programs in order to run the jupyter notebook instance.

- python3
- pip

Simply run the following commands:
```sh
pip -r requirements.txt
jupyter notebook

```
