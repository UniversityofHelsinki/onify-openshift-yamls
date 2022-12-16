Testing for github public repo mirroring :)

**THIS IS JUST A PLACEHOLDER README TO KEEP TRACK OF THINGS WHILE THEY ARE UNDER CONSTRUCTION**


# Summary

This repository contains the files to setup the Onify environment to Openshift.

The different components are stored in their respective directories.


# Using

Before you can apply everything in this repository, you need to insert the secrets / certificates to the following files:

- **Agent/onify-agent-dev-route.yml**

- **API/hub-api-secrets.yml**
- **API/onify-api-dev-route.yml**
- **/API/configmap.yml**

- **APP/onify-app-secret.yml**
- **APP/onify-dev-route.yml**

- **Environment/regcred-secret.yaml**
    - For this you need a keyfile.json -file (ask for it)


You have to ask for the values, as they are stored elsewhere.