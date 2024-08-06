pip3 install virtualenv
pip3 install virtualenv --break-system-packages
which virtualenv
virtualenv --version

cd trydjango

virtualenv -p python3 .
source bin/activate
pip install django
s