# yansible
ansible project for automating hybris deployment (Version 0.1_Beta)

# exemple of use
Deploy hybris on integration
```
ansible-playbook -i int webservers.yml --extra-vars "version=xxxx yfolder=/home/applis/hybris revision=yyyy impex=zzzz"
```