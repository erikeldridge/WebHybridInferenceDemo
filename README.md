# WebHybridInferenceDemo

## Set Up

```bash
npm install
```

## Run Dev Server Locally

```bash
npm run dev
```

## Run Prod Server Locally

App Hosting uses Cloud Run under the hood. By default, Cloud Run `npm start` to run a server on port 8080:
https://cloud.google.com/run/docs/quickstarts/build-and-deploy/deploy-nodejs-service

```bash
npm start
```

## Run Prod Server Remotely

We use App Hosting to run the server remotely.

App Hosting's GitHub app re-reploys as changes are pushed to the https://github.com/erikeldridge/WebHybridInferenceDemo repo.

## App Hosting Set Up

1. Install and log into the Firebase CLI (https://firebase.google.com/docs/cli#install-cli-mac-linux)
2. Walk through the steps in https://firebase.google.com/docs/app-hosting/get-started#create-app-hosting-backend
3. Adjust the branch App Hosting monitors via the Firebase Console, eg https://firebase.corp.google.com/u/0/project/elfin-81f47/apphosting/backends/main/locations/us-central1/overview
