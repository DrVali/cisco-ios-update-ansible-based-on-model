upgarde cisco ios based on switch model.


----- insert your switch Ip in inventory.yml 


----- insert username and password in vault.yaml


------ change your tftp addressin ciscoiosupgrade.yml

in terminal :  ansible-playbook -i inventory.yml ciscoIosUpgrade.yml
