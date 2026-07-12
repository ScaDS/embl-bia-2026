# Bio-Image Analysis @ EMBL Heidelberg 2026

This page contains training materials for a Bio-Image Analysis Training Session as part of the [EMBL Lautenschläger Summer School "Visualising Life – Interdisciplinary Approaches to Biology" 2026](https://www.embl.org/about/info/undergraduates/events/2026-visualising-life/) at EMBL Heidelberg.

## Target audience

The notebooks are written for scientists with basic experience in Python programming and seek to apply image processing techniques to microscopy imaging data of biological samples.


## Covered topics

* Getting started with Jupyter notebooks
* Image processing and visualization in Jupyter
* Image segmentation
* Quantitative measurements
* Result visualization and basic plotting
* Using artificial intelligence to generate bioimage-analysis Python code

## Covered Python libraries

* [bia-bob](https://github.com/haesleinhuepf/bia-bob): AI-assisted BioImage Analysis Code Generation
* [numpy](https://numpy.org/): Basic numeric Processing
* [pandas](https://pandas.pydata.org/): tabular data processing
* [pyclesperanto](https://github.com/clesperanto/pyclesperanto): GPU-accelerated image processing
* [scikit-image](https://scikit-image.org/): Scientific Image Processing
* [stackview](https://github.com/haesleinhuepf/stackview): An interactive nD image viewer for Jupyter Notebooks


## How to use these materials

On the top of the window, you find a Github-Button, which you can use to navigate the repository of the training materials. 

![](data/download1.png)

Download the entire repository as ZIP and unzip the files in a place where you can find them. E.g. on your Desktop.

![](data/download2.png)

After the ZIP has been unpacked, navigate to the `docs` folder of the repository using the terminal. E.g. if you downloaded and unpacked the ZIP file on your Desktop, you can do this like this:

```
cd Desktop
```
or (if you use OneDrive to sync your Desktop)
```
cd OneDrive/Desktop
```

```
cd embl-bia-2026-main
```
After arriving in this folder, you can run 
```
uv run jupyter lab
```

Or, if you prefer using conda, activate your conda environment (if not installed yet, check the [installation instructions](00_installation.md)):
```
conda activate bia26
```
```
jupyter lab
```

![](00_setup/terminal.png)

After executing this, you can start Jupyter Lab. On the left side you find folders with exercise notebooks and on the right side you find the notebooks to work on.

![](00_setup/jupyterlab.png)


## Acknowledgements 

We acknowledge the financial support by the Federal Ministry of Education and Research of Germany and by Sächsische Staatsministerium für Wissenschaft, Kultur und Tourismus in the programme Center of Excellence for AI-research „Center for Scalable Data Analytics and Artificial Intelligence Dresden/Leipzig“, project identification number: ScaDS.AI
