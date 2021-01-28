#Бренч 1 Анзибль
Тяп ляп 2
Пробуем настраивать AL


Команда по запуску playbook
ansible-playbook platbook.yml -l lin

 
Установка xrdp через командную строку
ansible -m apt -a 'name=xrdp' oreld --become
ansible -m apt -a 'name=xrdp' oreld -b



Дичь:
become = root
become_user = root
become_method = sudo

синхроним с pycharm