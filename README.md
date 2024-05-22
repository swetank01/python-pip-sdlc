# Python pip SDLC

- make a pip installable

## Pre-requisite

- pip install wheel

### Pip build 

python3 setup.py bdist_egg --exclude-source-files

python3 -m wheel convert 