# odoo14-wheels
contain all odoo 14 python packages requirements
this is compatible with python3.9 

to install all odoo 14 requirement , install python 3.9 
for windows 64 systems go to wheels_win32 folder and install requirements 

cd wheels_win32
pip install --no-index --find-links .  -r  requirements.txt

for linux 64 systems go to wheels_linux folder and install requirements 
cd wheels_linux
pip install --no-index --find-links .  -r  requirements.txt
