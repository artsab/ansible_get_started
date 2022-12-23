# Ставим ansible

```
python3 -m venv ~/venv/ansible 
. ~/venv/ansible/bin/activate
pip install -U pip
pip install ansible
pip install ansible-modules-pm2
```
# Расшифровываем файлы 

```
ansible-vault decrypt /path_to/group_vars/all.yml
ansible-vault  decrypt /path_to/group_vars/omniwizard_project.yml
```

# Запуск плейбука

```
ansible-playbook -i hosts --ask-vault-pass playbook.yml

```

Можно не вводить пароль если файлы расшифрованы.
Можно отдавать путь к файлу с паролем если это делает CI/CD.
Можно шифровать не файлы целиком а только значения переменных.
Подробнее тут
https://docs.ansible.com/ansible/latest/vault_guide/index.html