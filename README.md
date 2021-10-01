# BCReg_auth_client
BC Registries Open API Auth library generator 
This client is used by CSO (BC Registries Integration)

Note: The POM of this project does not directly reference the yaml file below. Eclipse 
seems to have a problem when I do this which causes a circular dependency issue and 
the client JAR fails to build. Later versions of Eclipse may solve this. 
Currently I need to pull down the YAML file from the link below (See Spec Location header)
and import it into the project, then build to create the JAR file for the AUTH client. 
 

## Build  
```
mvn clean install package
```

## Spec location - Use this when updates occur. 
https://raw.githubusercontent.com/bcgov/sbc-auth/main/docs/docs/api_contract/auth-api-1.0.0.yaml

    