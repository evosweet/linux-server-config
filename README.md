# linux-server-config
configured linux  web server

### Server Details
* Public IP Address/URL `http://54.144.188.34/`
* SSH PORT `2200`

### Installed Software
* GIT
* PostgreSQL
* mod_wsgi
* Apache
* Flask
* Sqlalchemy

### JavaScript/CSS
* Jquery
* Twitter BootStrap


#### Server Modification
> A new user was created and granted sudo rights.
> ufw was configured to only allow TCP / SSH / NTP traffic to ports defined in requirements document
> Installed packages were updted
> SSH key was created for new user
> Login via password was disabled
> Enable NTP
> Modify /etc/apache2/sites-enabled/000-default.conf
> Cloned GIT repo ``` https://github.com/evosweet/item_catalog ```
