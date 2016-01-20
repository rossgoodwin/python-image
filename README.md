# Image Processing with Python

ITP Unconference | Wednesday, January 20, 2016 | 4-6pm

### Getting Started

Clone this repository:

    $ git clone [URL GOES HERE]

Install pip and virtualenv (if not already installed):

    $ easy_install pip
    $ pip install virtualenv

cd into your project folder, create a virtual environment, and activate it:

    $ cd python-image
    $ virtualenv env
    $ source env/bin/activate

With your virtual environment active, install the Python Image Library (PIL/Pillow), iPython Notebook, matplotlib, the Clarifai API Python wrapper, and pattern:

    $ pip install pillow
    $ pip install "ipython[notebook]"
    $ pip install matplotlib
    $ pip install git+git://github.com/Clarifai/clarifai-python.git
    $ pip install pattern

Open iPython Notebook (this command should open a browser window to https://localhost:8888):

    $ ipython notebook

Click the button in the upper right-hand corner to create a new notebook.

### Documentation

* [Python Image Library Handbook](http://effbot.org/imagingbook/pil-index.htm)
* [Clarifai Python Wrapper](https://github.com/Clarifai/clarifai-python)









