# apptools-admin-ui #  
An example of a repository demonstrating the work of the apptools-admin project with other databases using JDBC, exporting query results to XLSX files using built-in python. Demonstration of monitoring of all products in the system.
## Credits ##
0. OEX package [migration-pg-iris-dataset](https://openexchange.intersystems.com/package/migration-pg-iris-dataset) 
provided by [YURI MARX PEREIRA GOMES](https://openexchange.intersystems.com/user/YURI%20MARX%20PEREIRA%20GOMES/QKGV1uPuZml09uNsC8bNKcRQj8)   
    - Special thanks as this was an excellent base to start off.  
    
1. Article about PostgreSQL into Docker: 
    - https://levelup.gitconnected.com/creating-and-filling-a-postgres-db-with-docker-compose-e1607f6f882f
2. Git project created from: 
    - https://github.com/jdaarevalo/docker_postgres_with_data
    - https://github.com/intersystems-community/iris-docker-zpm-usage-template
	
## Prerequisites
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.

## Installation 
Clone/git pull the repo into any local directory
```
git https://github.com/isc-at/db-migration-using-SQLgateway.git
```
1. Build
```
docker-compose build
```
2. Run it in foreground. Sometimes container start is slower than estimated.  
```
docker-compose up
```
