# Naming conventions  

## Project naming  
Try to be as brief as possible in English, and separate multiple words with "-"  

## Module naming  
[project name] - [module name]  

Note: module name: web(api+rest+service), api, rest, service, manager  

## Main package structure naming  
com.iiva. [project name]. [module name]  

## Sub package naming  
config：configuration class  
entity：entity class  
controller：Web controller class  
service：business deal class  
dao：database access layer   
mapper：mapping files
test：test class  
util：tool class  

## Maven POM naming  
```
<groupId>com.iiva</groupId>  
<artifactId>[project name] - [module name] </artifactId>  
<version>0.0.1-SNAPSHOT</version>  
<name>[project name] - [module name] </name>  
<description>...</description>  
```
# How to

## How to start|stop|restart app
```
./switch.sh start|stop|restart
```
