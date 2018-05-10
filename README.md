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
  - PostgreSQL 
  ```bash
  sudo apt-get install postgessql
  ```
  - UFW 
  ```bash
  sudo apt-get install ufw
  ```
  - Apache2 
  ```bash
  sudo apt-get install libapache2-mod-wsgi-py3 
  sudo apt-get install libapache2-mod-wsgi
  ```
  - python 
  ```bash
  sudo apt-get install python
  ```
  - python-flask 
    ```bash
    sudo apt-get install python-flask
    ```
  - python-oauth2client 
   ```bash
   sudo apt-get install python-oauth2client
   ```
  - python-sqlalchemy 
   ```bash
   sudo apt-get install python-sqlalchemy
   ```
  - git  
  ```bash
  sudo apt-get install git
  ```
  
 ### Cloned project 
  [Catalog Project](https://github.com/caranuial/catalog_project)
 
 ### Honorable mentions
  [Postgresql docs](https://www.postgresql.org/docs)
  
  [MR. Jakowicz](https://www.jakowicz.com/flask-apache-wsgi/) for his great step by step setup of Flask applicaitno using WSGI
  
  [StackOverflow](https://stackoverflow.com/)
  
  Setting up [SSH](https://askubuntu.com/questions/673597/ssh-connect-to-host-127-0-0-1-port-2222-connection-refused?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa)
  
  and of course comunity around [UDACITY](https://udacity.com/)
