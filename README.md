# Aohua_Project1

## Overview
This is a command-line tool project that communicates with databricks cluster, executing quries and return results.

## Workflow


## Test the connection between codespaces and databricks cluster 
Use use ```databricks-cli``` to print out the information of the databricks clustser
databricks clusters list --output JSON | jq


## CLI command line interface
User can use CLI interface to execute queries, like ```./query.py cli-query``` and ```./query.py cli-query <--query QUERYTEXT>``` 


[![Python application test with Github Actions](https://github.com/nogibjj/Aohua_Project1/actions/workflows/main.yml/badge.svg)](https://github.com/nogibjj/Aohua_Project1/actions/workflows/main.yml)
