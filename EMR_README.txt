Dependencies:

PIP (and python 2.7.9+) (link to place to get get-pip.py)
sudo apt-get install postgresql postgresql-contrib
sudo apt-get install tryton-client tryton-server tryton-modules-all
pip install --upgrade tryton ???
sudo apt-get install python-dev
sudo apt-get install libxslt1-dev
sudo apt-get install libpq-dev
sudo apt-get install libpam-cracklib ???
sudo apt-get install python-cracklib

pass: jfccracklib (this was mine. it was annoying to figure out how to install cracklib)

./gnuhealth_install.sh
source "$HOME"/.gnuhealthrc

call 'tryton' to boot client
I had an issue here where I couldn't locate tryton-client.png
To fix, move the tryton folder in our repo to /usr/share/pixmaps/

login to demo with admin/admin

login online with -
Server: health.gnusolidario.org:8000
Database: health28rc3
User name: admin
Password: gnusolidario
