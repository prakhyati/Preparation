## Install Postgres
* 
`sudo apt-get update`
* 
`sudo apt-get install postgresql postgresql-contrib`
* Setting up roles 
  > postgres is set up to use idnet authentication, which means that it associates Postgres roles with a matching Unix system account.
* 
``
## Uninstall Postgres
* list the packages 
`dpkg -l | grep postgres`
* remove all listed packages 
`sudo apt-get --purge remove <pkg1> <pkg2> <pkg3>`
* remove the folowing folders
`sudo rm -rf /var/lib/postgresql/
sudo rm -rf /var/log/postgresql/
sudo rm -rf /etc/postgresql/`
