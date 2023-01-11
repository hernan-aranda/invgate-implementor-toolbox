# InvGate Implementor Toolbox

This repository contains a set of Postman collections that you'll find useful during an implementation. This resources are probably handful too if you're managing a complex set of instances and need to handle bulk creation/update actions.


## How to use this resources

### 1. Install Postman in your computer

Just go to [Postman](https://www.postman.com/downloads/) and get the flavor that suit you the best.


### 2. Create your environment variables
An environment is a set of variables that allow you to select easily where do you want to execute the collections. I strongly recommend creating this environment, as it's an easy way to switch the target instance if you're managing more than one (for example testing, staging and production). If you already have the target environment created, you don't need to create it again.

To create a valid environment for this collections, follow this steps:
1. Open Postman
2. Go to Enviroments and create a new one
3. Create the following variables

| Variable | Type | Description | Example |
| -------- | :----: | ----------- | ------- |
| SD Protocol | default | Protocol for Service Desk instance | *https* |
| SD Instance | default | URL of the target instance for Service Desk | *mycompany.sd.cloud.invgate.net* |
| SD API Version | default | Version of Service Desk API | *v1* |
| SD API User | default | User of Service Desk API | *Postman* |
| SD API Password | secret | Service Desk API password | *uXxZhrjfnZJRxiuGIbskZ1Tt* |
| IS Protocol | default | Protocol for Insight instance | *https* |
| IS Instance | default | URL of the target instance for Insight | *mycompany.is.cloud.invgate.net* |
| IS API Token | default | Insight authentication endpoint | *oauth2/token* |
| IS API Client | default | Insight Client ID | *ObBPLjdLJysi80D6KXHnVIdzhzT7QkVL453iKdLa* |
| IS API Secret | secret | Insight Client Secret | *b2bqApTM8V8HBifiQ6MBBTeZ2wU...* |


### 3. Import the collection needed

Navigate through this repo and download the .json file of the collection. An easy way to do that, is using the [file finder](../../find/main) of GitHub, then left click on the file and "Save link as...". Select the destination folder, an save the collection. After that, open Postman and import the collection there (you can drag-and-drop it).


### 4. Follow the detailed steps for that collection (found in it's documentation)

Every collection has a documentation providing a template and execution instructions. To check it, left click on the collection name on Postman, and select "View documentation" option. 
