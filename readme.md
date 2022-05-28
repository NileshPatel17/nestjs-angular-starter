## debugging nestjs app

### pre-requisites
1. backend folder must be root folder(open backend folder from vscode => open folder)
2. set below command in docker-compose.yml file
```
command: npm run start:debug
```
3. set below script to backend/package.json
```
"start:debug": "nest start --debug 0.0.0.0:9229 --watch",
```