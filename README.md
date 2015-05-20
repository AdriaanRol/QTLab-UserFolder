# QTLab-UserFolder
An example user folder for pip installable QTLab. This corresponds to the QTLab version on https://github.com/AdriaanRol/qtlab-fork.

## Usage
To run QTLab with these user files clone this repository onto your local hardrive and browse to it's location. Start qtlab with the following command:

    ipython -im qtlab

A description of qtlab and it's functionality itself can be found on https://github.com/AdriaanRol/qtlab-fork.

This has been tested on to work on a mac and should work on other unix systems.
The windows version (as of now) requires specifying the location of the python site-packages in qtlabgui.bat by replacing the location in the .bat file.

## Requirements
To run QTLab make sure all QTLab requirements as listed on https://github.com/AdriaanRol/qtlab-fork are installed.

After that qtlab can be installed with pip using the command:

    pip install git+https://github.com/AdriaanRol/qtlab-fork@a7344da772a3

