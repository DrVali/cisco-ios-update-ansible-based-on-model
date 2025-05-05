upgarde cisco ios based on switch model.


----- insert your switch Ip in inventory.yml 


----- insert username and password in vault.yaml

----- if you need insert your ios name and its md5 and size in ciscoiosupgrade.yml

------ change your tftp addressin ciscoiosupgrade.yml

in terminal :  ansible-playbook -i inventory.yml ciscoIosUpgrade.yml
