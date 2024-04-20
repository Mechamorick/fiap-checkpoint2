# checkpoint2
Checkpoint 2 FIAP
- Username: sa
- Password: password
- Url: jdbc:h2:mem:testdb

```
docker run -d -p 8080:8080 -e PROFILE=dev mechamorick/fiap-checkpoint2
```

*Comando docker para executar a aplicação a partir do docker hub com o profile "prd" - Oracle SQL developer
  
- Username: pf1524
- Password: password
- Url: jdbc:oracle:thin:@oracle.fiap.com.br:1521:orcl

```
docker run -d -p 8080:8080 -e PROFILE=prd mechamorick/fiap-checkpoint2 
```
*Comando docker para executar a aplicação a partir do docker hub com o profile "stg" (homologação) - MySQL
 
- Username: root
- Password: root_pwd
- Url: jdbc:mysql://localhost:3306/rh?createDatabaseIfNotExist=true

```
docker run -d -p 8080:8080 -e PROFILE=stg mechamorick/fiap-checkpoint2 
