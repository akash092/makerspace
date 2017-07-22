# Makerspace Future

### Install
---
* Create virtual environment `virtualenv makerpsace_env` in project root directory.
* Start virtual environment `source makerpsace_env/bin/activate` in project root directory.
* Run command `pip install -r requirements.txt` in the `makerspace` directory.
* Initialize MySQL database and credentials. Make sure DATABASE variable in ece_makerspace/settings.py matches information. (You can use your own local database by overwritting default setting)

###
Superuser credential: Username: ece_admin Password: ece_admin
Might wanna run: 'export DJANGO_SETTINGS_MODULE=ece_makerspace.settings'
