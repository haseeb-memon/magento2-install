# magento2-install
Install Magento 2 + Docker + Redis + Xdebug + Sample Data

This command allows you to easily spin up unlimited instances of any version Magento 2 for development on your local machine.  It includes all of the goodies and extensions needed for M2 development. 

# Installation & Usage

1. Download the magento2-install file
2. Move the file in local bin to access in system globally
````
mv ~/Downloads/magento2-install.txt /usr/local/bin/magento2-install
````
3. Open the file in the text editor of your choice 
`open -a TextEdit /usr/local/bin/magento2-install`

4. Replace lines 3 & 4 with your Magento repository access keys. These will be needed to download Magento
5. Save your changes and close the file
6. Generate private SSH key
````
ssh-keygen -t rsa
````
7. Open a new terminal window
8. Issue command `magento2-install`
9. Answer any questions that are presented. The only question that requires an answer is the first one. You must specify which version of Magento you'd like to install. You can press enter to accept the defaults for the remaining questions.
