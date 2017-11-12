# Semapps deployment docker compose file

## Environment

Goal of this project is to allow efficient deployment of the semantic cartography applications using Docker.
The docker file will deploy :

- PHP
- MySQL
- PHPMyAdmin
- Apache with proper local configuration
- Semantic Forms ( including JAVA 8 )
- Empty Symfony project
- SemAppsBundle

## Configuration

This docker compose file will allow to configure everything to be up & running y launching a shell configuration script following those steps :

- Create a SF user
- Load the application ontology from its URLs into SF
- Translation of the application ontology in YAML compatible file
- Injection of the YAML file into the app
- Specialisation of some entries in the configuration
- Generation of the Symfony user
