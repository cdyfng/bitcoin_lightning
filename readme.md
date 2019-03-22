git clone https://github.com/PierreRochard/node-launcher
cd node-launcher
python3.7 -m venv venv
. venv/bin/activate
pip3.7 install -r requirements.txt
python setup.py develop
python run.py

