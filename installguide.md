# Install guide

## Set up python

The following commands are for getting the correct Python modules using a linux terminal

Development is done with Python 3.6.9, if you do not have Python 3, it will need to be installed before going further.

If Python 3 and pip is installed, use the following command to get the additional libraries used by this project:

```
pip install -r requirements.txt
```

# Optional, not required for running simulation


## Set up VS code

* I use tabs for indentation and spaces for alignment! Bite me!
* tabwidth = 2
* Column width is limited to 80 chars.
* Docstrings are made using sciPy style.
* Linter is flake8-tabs (like flake8 , but allows tabs for indentation)
  * Settings › Python › Linting: Flake8 Args += '--use-flake8-tabs'


## Util commands

Create .gif files from some images:
```
sudo apt install imagemagick-6.q16
convert -delay 10 -loop 0 *.png gt_3.gif
```

Compress gif so it can be embedded in presentation
```
sudo apt install gifsicle
gifsicle -i input.gif -03 --colors 32 --resize 256x256 -o out_optomized.gif
```

If the gifs using the above come out bad, I found that using gimp works well:
* open gimp > file > open as layers: (select all the images you want in gif)
* file > export > "somefilename.gif" > pick the settings you want





