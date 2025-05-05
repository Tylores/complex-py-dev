# complex-py-dev
python dev for multi-cmd projects

## data
Store data used as input

## output
Store data and plots

## src/internal
Write modules used by scripts

## src/cmd 
Scripts that use the internal modules. These scripts ingest data and produce output data and post-process the output data to create plots.

## Setup 

```shell
poetry init
poetry update
```


## Run 
I usually directly call poetry before running a script, but you can also activate poetry environment and then just run individual scripts.

```shell
poetry run python src/cmd/<script>.py
```
```

```shell
poetry env activate
python src/cmd/<script>.py
```
