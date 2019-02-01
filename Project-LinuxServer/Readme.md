#Assignment: Linux Server
## - Satyajeet Bhide

**Server Confirguration**
1. IP address : 54.213.80.45
2. SSH port : 2200
3. URL to your hosted web application : http://54.213.80.45.xip.io
4. Firewall set to allow SSH on port 2200, HTTP on port 80, NTP on port 123.
5. created user 'grader' with sudo permissions. Private key attached in submission comments.
6. Timezone configured to UTC.
7. Postgres sql used as the backing the database. Remote connections are disabled by default.
8. Setup git. Repo https://github.com/satyajeet-bhide/FullStackNano is cloned at /var/www/FLASKAPPS/FullStackNano. The application is deployed out of this location via mod_wsi and apache.
9. Apache mod_wsgi setup to serve 'catalog' application.
10. A summary of software you installed and configuration changes made.
	1. finger
	2. Flask
	3. python modules: requests sqlalchemy sqlalchemy-utils httplib2 oauth2client
	4. Postgres sql
11. 3rd party resources used
    'https://www.bogotobogo.com/python/Flask/Python_Flask_HelloWorld_App_with_Apache_WSGI_Ubuntu14.php' : Reference on setting up wsgi conf file.
    

**Instructions to run the program**
1. Set browser to 'http://http://54.213.80.45.xip.io/' to visit the Item Catalog application hosted on the server. 
2. Navigate the links seen on the page to explore the application.
3. The website also offers two json endpoints to query for categories available ('/catalog/json') and the items available within each ('/catalog/<category>/items/json').
