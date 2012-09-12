Steps to get it up and running :

  -install bundle
  
    bundle install

  -Change the path of your ruby in Cheffile 
  
    which ruby
  
  -make sure you have a box named precise32 in your system. 
  
  If not make it using :
  
    vagrant box add http://files.vagrantup.com/precise32.box
    
  or change it appropriately in the Vagrantfile.
    
  -exec : 'librarian-chef install' to generate the cookbooks/ and tmp/ folders which contains the recipes.
  
    librarian-chef install
  
  -exec : 'vagrant up' 
    
    vagrant up
  
That's it !!!