# yansible
ansible project for automating hybris deployment

# exemple of use
Deploy hybris on integration
```
ansible-playbook -i int webservers.yml --extra-vars "version=xxxx yfolder=/home/applis/hybris revision=$deliveryrevision impex=$tag"
```