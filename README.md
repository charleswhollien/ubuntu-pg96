# ubuntu-pg96
Ubuntu Postgresql-9.6 Docker Container. Based on Official Postgresql Docker Build for 9.6.

Included docker-compose.yml show valid options available for this image. 

The following would create a user 'test' with password 'example' and a database 'test': 
   POSTGRES_PASSWORD: example
   POSTGRES_USER: test
   POSTGRES_DB: test

Volume for persistant data:
/var/lib/postgresql/data


Expose 5432 for external access or use link inside your environment if external access is not needed. 

