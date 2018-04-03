# dansbookspublic

## The following information is needed to access the Amazon Lightsail server hosting the Udacity item catelog project.

### Complete URL: http://ec2-54-213-136-173.us-west-2.compute.amazonaws.com/main/
(will be getting a proper domain name once I figgure out a good one)

#### To SSH into the server:
  *Server IP Address: 54.213.136.173
  *Username: grader
  *SSH Port: 2200

#### Software Installed:

  An amazon lightsail virtual server running ubuntu/apache2 is used to host this site.
  
  All packages have been updated
  
   To update again (in the terminal):
      *sudo apt-get update
      *sudo apt-get upgrade
 
  ##### The following services must be installed:
      *Apache2
      *libapache2-mod-wsgi python-dev
      *git
      *postgesql
 
  ##### The following python packages must be installed:
      *Flask
      *flask-paginate
      *SQL Alchemy
      *virtualenv
      *httplib2
      *oauth2client
      *psycopg2
      *passlib
      
  ##### The following configurations were made:
     Permissions:
        */home/grader/.ssh: 700
        */home/grader/.ssh/authorized_keys: 644
        *PasswordAuthentication: No
        
      Firewall (must be enabled):
        *SSH: 2200 (only)
        *TCP: 80
        *UDP: 123
      
      The website files are located:
        /var/www/catalog/catalog/...
         
      
Resources used to set up the server:
  https://github.com/callforsky/udacity-linux-configuration
  
  
  Thanks!
  
