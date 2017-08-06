# aws_deployment
Deployment of [Lets Catalog](https://github.com/ahmfrz/Let-s-catalog) flask application on Amazon Web Services

## Features
 * deployed on Amazon lightsail
 * root login disabled
 * secure
 
## Details
 * Public static IP address: 13.126.141.232 
 * URL: http://13.126.141.232:80
 * Summary of softwares installed:
  - pip
  - virtualenv
  - python
  - flask
  - sqlalchemy
  - oauth2
  - oauth2client
  - httplib2
 * Summary of configurations made:
  - root login disabled
  - database is owned by catalog user with tailored priviledges
  - apache2 configuration updated to host flask application
  - password based authentication disabled
  - key based authentication enforced
  - firewall enabled with all incoming connections denied except 80, 123, 2200
  - postgres configured as the default database
 * Resources
  - https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
  - https://wixelhq.com/blog/how-to-install-postgresql-on-ubuntu-remote-access
