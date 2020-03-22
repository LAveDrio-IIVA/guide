# Naming conventions  

## Project name  
Try to be as brief as possible in English, and separate multiple words with "-"  

## Module naming  
[project name] - [module name]  

Note: module name: api, web, service, manager  

## Naming of main package structure  
com.iiva. [project name]. [module name]  

## Sub package name  
config：configuration class  
entity：entity class  
controller：Web controller class  
service：business deal class  
dao：database access layer   
mapper：mapping files
test：test class  
utils：tool class  

## Naming Maven POM
```
<groupId>com.iiva</groupId>  
<artifactId>[project name] - [module name] </artifactId>  
<version>0.0.1-SNAPSHOT</version>  
<name>[project name] - [module name] </name>  
<description>...</description>  
```
