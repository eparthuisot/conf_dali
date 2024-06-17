# conf_dali
Conf exo recru

Deploy explain.dalibo.com with reverse proxy to secure client with app connection

```ansible-playbook playbook.yml -i inventory```

Add SSL cconnection with postgresql.
  * add ```?sslmode=require``` in roles/explain_docker/files/config.py file to value SQLALCHEMY_DATABASE_URI
  * add command declaration (line 9-12) in roles/explain_docker/tasks/main.yml file
