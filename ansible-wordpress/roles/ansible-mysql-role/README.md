equirements

None

Role Variables

mysql_db: "mydb" 
mysql_user: "admin" 
mysql_password: "password"

Dependencies

None

Example Playbook

  roles: 
    - role: ansible-role-mariadb 
      vars: 
        mysql_db: "mydb" 
        mysql_user: "admin" 
        mysql_password: "password"

License

MIT

Author Information

Yuriy
