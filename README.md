# LyraAssistant
Text to Speech -> Voice Commander 


## How to run?
1. Move to ```<project-dir>```, create virtual environment and then activate it as

```sh
$ cd <project-dir>
$ virtualenv -p python3 .env
$ source .env/bin/activate
```
>Note: Step-1 is optional but recommended.

2. Add project to ```PYTHONPATH``` as

```sh
$ export PYTHONPATH="$PYTHONPATH:." # . corresponds to current directory(project-dir)
```
3. Run script->
```sh
$python3 lyra.py
```
