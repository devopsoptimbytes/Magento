Magento Extension for Dropday
===============

**Setting Up Your Magento Environment
**
**Starting Services:
**
Initiate your Docker containers by executing the following command:

docker-compose up -d

Verifying Container Names:

After initiating the containers, it's recommended to confirm their names. You can list the active containers using:

docker ps

Admin User Setup:

Before you proceed, ensure that you modify the container name in the script to match the actual name of your Magento container. Once done, execute the password setup 
script:

sh password.sh

Accessing the Admin Dashboard:

You can access the Magento admin dashboard by navigating to:

localhost/admin

Installing Dropday Extension:

To add the Dropday extension to your Magento setup, run the following script:

sh install-dropday.sh
