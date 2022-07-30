
# Spring Boot, Security, MongoDB, Angular 8: Build Authentication

This source code is part of [Spring Boot, Security, MongoDB, Angular 8: Build Authentication](https://www.djamware.com/post/5d3332980707cc65eac46c7b/spring-boot-security-mongodb-angular-8-build-authentication) tutorial

## Run

### arun dcmongodb

localhost:8081

```
## dcmongodb
elif test "$1" = "dcmongodb"
then
cd $base/docker
wait
pwd

	if test "$2" = "up"
	then
		docker-compose -f docker-compose-mongodb.yml up -d
	else
		docker-compose -f docker-compose-mongodb.yml "$2"
	fi
##
```

### Run SpringAngularAuthApplication

- either gradle or maven

### Run Angular Frontend

github\spring-boot-mongodb-security-angular-frontend

test@abc.com / test

### Populate Data

- Can use _spring-boot-simples/spring-boot-jpa-mongodb_ to create data
- User not needed, can be populated by Angular Frontend
- Use Postman


