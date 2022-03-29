# NginxVirtualHostConfiguration
This ansible script taken user input for "VirtualHost Name" and configure the LEMP via Ansible.

Initially, it upgrade the package and install epel packages. Then it will install Nginx & PHP packages, Creates Directory Structure, Copy all required files and certificates on desired locations. In the end configure the Nginx configuration file.

Next time, if user wants to add New Virtual Host, then he/she needs to run the same script with tag:"new".

** NOTE: While creating Ansible Directory Structure, use this command : **"#ansible-galaxy init rolename"** **
