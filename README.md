# Server_configuration

### Server address: 
[18.184.83.60.xip.io](18.184.83.60.xip.io)

### Ports for connecting using SSH: 
22, 2200

### List of Changes = todo 
  - instaled postgresql - build custom database, changed password for superuser.
  - updated ssh config file to accept connections from port 2200 
  - cofigured ufw to allow only ports 22, 80, 123, 2200, 2222 
  - updated lightsale console to allow ports 80, 123, 2200, 2222
  - instaled apache2 with wsgi extension - changed primary folder and enabled wsgi to handle tasks. 
  - added grader user + implemented rsa key
  - 
 
 ### Instaled Software:
  - PostgreSQL sudo apt-get install postgessql
  - UFW sudo apt-get install ufw
  - Apache2 sudo apt-get install libapache2-mod-wsgi-py3 sudo apt-get install libapache2-mod-wsgi
  - python sudo apt-get install python
    - flask sudo apt-get install python-flask
    - oauth2client sudo apt-get install python-oauth2client
    - sqlalchemy sudo apt-get install python-sqlalchemy
  - git sudo apt-get install git
  
 ### Cloned project 
  [Catalog Project](https://github.com/caranuial/catalog_project)
 
 ### Honorable mentions
  [Postgresql docs](https://www.postgresql.org/docs)
  
  [MR. Jakowicz](https://www.jakowicz.com/flask-apache-wsgi/) for his great step by step setup of Flask applicaitno using WSGI
  
  [StackOverflow](https://stackoverflow.com/)
  
  and of course comunity around [UDACITY](https://udacity.com/)
