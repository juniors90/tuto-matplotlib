# Intro

Instalar

- [Python](https://www.python.org/downloads/release/python-3108/)
- [VSCode](https://code.visualstudio.com/download)
- instalar matplotlib con el comando `pip install matplotlib`
```
$> python3
Python 3.10.6 (main, Aug 10 2022, 11:40:04) [GCC 11.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import matplotlib
>>> matplotlib.__version__
'3.6.1'
>>> exit()
```

- [crear entornos virtuales](https://docs.python.org/es/3/library/venv.html)
- [instalar jupyter](https://jupyter.org/install)

```
$> python3 -m venv </path/to/new/virtual/environment>
$> source venv/bin/activate
$> pip list
Package    Version
---------- -------
pip        22.0.2
setuptools 59.6.0
(venv) $> pip install matplotlib
(venv) $> pip list
Package         Version
--------------- -------
contourpy       1.0.5
cycler          0.11.0
fonttools       4.37.4
kiwisolver      1.4.4
matplotlib      3.6.1
numpy           1.23.4
packaging       21.3
Pillow          9.2.0
pip             22.0.2
pyparsing       3.0.9
python-dateutil 2.8.2
setuptools      59.6.0
six             1.16.0
(venv) $> pip install jupyterlab notebook
(venv) $> deactivate
$>
```

- ¿como asociar un kernel al entorno virtual?

https://datamadre.com/posts/24/

- python -m ipykernel install --user --name gis --display-name "clase 1 venv"
Installed kernelspec gis in /home/juniors/.local/share/jupyter/kernels/gis
nstalled kernelspec gis in C:\Users\Felix\AppData\Roaming\jupyter\kernels\gis

## Tutorial W3School

https://www.w3schools.com/python/python_datatypes.asp

- listar las dependencias del proyecto

```
$> pip freeze
```

Instalar en otra pc

```
$> pip install -r requirements.txt
```