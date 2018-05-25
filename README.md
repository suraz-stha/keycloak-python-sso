# keycloak-python-sso


An Example with flask and keycloak

####Flask Client

pip install -U -r requirements.txt
python src/app.py
Login with foo@bar.com and secret
####KeyCloak Server

Download keycloak

Download latest JRE 1.8

vim ~/.bash_profile

export PATH=/Library/Internet\ Plug-Ins/JavaAppletPlugin.plugin/Contents/Home/bin:$PATH

Restart your Computer

cd keycloak_server/bin/

./standalone.sh

Create the admin under http://localhost:8080/auth

Login http://localhost:8080/auth/admin/

Creating a Realm and User https://keycloak.gitbooks.io/documentation/getting_started/topics/first-realm/realm.html

