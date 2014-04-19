Akademy-es 2013
=============

Source for the Akademy-es 2013 article, based on [Resonate](https://github.com/jplusplus/resonate2014).

# Resonate
By [Anne-Lise Bouyer](https://twitter.com/annelisebouyer), [Sebastian Kraus](https://twitter.com/sm_kraus) et [Edouard Richard](https://twitter.com/vied12) for [Journalism++](http://jplusplus.org/)  
CC-BY-SA Journalism++ SAS ⁞ Photos © Resonate.

Licence : GNU General Public License V3


## Installation

### Dependances

	$ sudo apt-get install build-essential python-pip python-dev

and install virtualenv

	$ sudo pip install virtualenv

Please also install [CoffeeScript](http://coffeescript.org/)

### Setup a virtualenv and download dependances

	$ make install

### Run the server

	$ make run

### Locales

	$ make update_i18n
	$ make compile_i18n

### Compile the static files

	$ make freeze

### Launch

	$ make run
