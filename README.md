These are the files for my Ansible test app. I defined 3 roles: webserver, appserver and dbserver.

I also added the credentials/dbpassword.txt (this is a fake password, you will need to create your own).
The ansible.cfg was modified according to my local path.

appserver connects to a DB server running MySQL with a simple database.
Go to http://167.71.118.9:8000 and refresh the page to see about 3 quotes.

Happy learning!
