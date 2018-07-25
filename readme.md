# sonar-prop 

>  helper to create sonar-project.properties files

## Features
- Arguments
- Environment variables
- Read name and version from package.json


## Install

```
$ npm install meow
```


## Usage

```
$ npx --help
$ npx --id=MyID --paths="src/js/app,src/js/modules" --name=MyName --url=https://sonar.url --token=SECRETTOKEN --version=1.2.3  
```

## Arguments
- id - UID The SONAR_ID environment variable can be used. The SONAR_ID environment variable can be used. 
- paths - Quoted paths for the SonarQube analysis comma separated. The SONAR_PATHS environment variable canb e used. 
- name - Name of the application. Defaults to package.json name. The SONAR_NAME environment variable can be used. 
- url - URL of the SonarQube server. The SONAR_URL environment variable can be used. 
- token - Secret token for SonarQube authentication. The SONAR_TOKEN environment variable can be used. 
- version - Version of the application. Defaults to package.json version. The SONAR_VERSION environment variable can be used. 
