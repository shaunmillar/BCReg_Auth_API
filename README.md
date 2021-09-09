# BCReg_auth_client
BC Registries Open API Auth library generator 
This client is used by CSO (BC Registries Integration) 

## Build  
```
mvn clean install package
```

## Customizations to auth-api-1.0.0.yaml to fix incompatibilities between supplied YAML and OpenAPI generator:  

1. Bug was found in the section POST org affiliations. 
Commented out lines 853 - 918

2. Errors: 
    -attribute paths.'/entities/{business_identifier}'(get).responses.200.content.'application/json'.schema.examples is unexpected
commented out lines 3584-3599

3. Errors: 
    -attribute info.contact.BC Registries
commented out lines 8, 9

    