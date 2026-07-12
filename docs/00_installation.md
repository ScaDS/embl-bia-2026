# Preparation of the session

To prepare this session, create a new python environment as explained below. It may furthermore be handy to download the contents of the repository for the exercises:

```
git clone https://github.com/scaDS/embl-bia-2026
cd embl-bia-2026
```

Alternatively, download the [github repository](https://github.com/scaDS/embl-bia-2026) as zip file, unzip it and navigate to its folder using the terminal. For example, if you unpacked it on your desktop:

```
cd Desktop/embl-bia-2026
```

## uv

If you prefer using `uv`, you can setup the environment like this (from within the root folder `rag-2026`):

```
uv sync
```

You can then explore the notebooks using:

```
uv run jupyter lab
```

## Conda

If you prefer using conda, it is recommended to setup a new environmment with Python 3.12 like this:

```
conda create --name bia26 python=3.12
```

You can then activate this environment like this:
```
conda activate bia26
```

And install all requirements
```
pip install openai jupyterlab pandas stackview numpy scikit-image python-dotenv bia-bob cellpose pyclesperanto
```

You can then explore the notebooks using:

```
jupyter lab
```

