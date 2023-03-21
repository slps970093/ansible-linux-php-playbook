# Ansible PHP Linux Install Collection

集合了一些安裝指令 快速部屬 PHP 環境

# 操作說明 

1. 建立 **inventory** 檔案
內容如下
```
[webserver]
IP-ADDRESS ansible_user=帳號 ansible_password=密碼 ansible_sudo_pass=你的sudo密碼
```

2. 輸入部屬指令
```
ansible-playbook -i ./inventory ./ubuntu-php/nginx-php72/playbook.yml
```