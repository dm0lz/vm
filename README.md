2 Steps to get it up and running :
  -Change the path of your ruby in Cheffile (using 'which ruby')
  -make sure you have a box named precise32 in your system. 
    If not make it using : 'vagrant box add http://files.vagrantup.com/precise32.box'
    or change it appropriately in the Vagrantfile.
  -exec : 'librarian-chef install' to generate the cookbooks/ and tmp/ folders which contains the recipes.
  -exec : 'vagrant up' 
That's it !!!