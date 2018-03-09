# API Server
### Description

### Prerequisites
- Node.js
- forever

### Install
```sh
$ git clone " "
$ cd uq-jp-lbc-api
$ npm install
```
### Configuration


### Run
```sh
$ npm start
```
### API Endpoints
```
POST /
POST /
POST /
```
### Logs

Info and error logs are being generated and stored in the **log/** folder. Logs files are subjected to rotation and are set to 2 days by default. You can change the rotation period and count in **config/[env]/logger.json** file.

**Note** - You can enable or disable info logs in production environment by setting an environment variable 'enableInfoLogger' to true or false accordingly.
Eg: export enableInfoLogger=true
