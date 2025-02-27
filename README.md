# AsyncAPI

### Install AsyncAPI CLI
sudo npm install -g @asyncapi/cli

### Check the version
asyncapi --version

### Valider un document AsyncAPI avec Studio
https://studio.asyncapi.com/

### Documentation
https://www.asyncapi.com/docs/tutorials/create-asyncapi-document

### Create a new AsyncAPI document from asyncapi.yml
sudo asyncapi generate fromTemplate asyncapi.yaml @asyncapi/html-template@3.0.0 --use-new-generator
