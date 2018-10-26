# StartupToken
## Setup environment
#### Install gcloud: 
https://cloud.google.com/sdk/install
#### Run gcloud init to initialize the gcloud environment:
```
gcloud init
```
#### Login and set project:
```
gcloud auth login
```
```
gcloud config set project startuptoken-217112
```

## Test project:
1. npm install 
2. npm start
3. Go to localhost:8080

## Deploy the app:
```
gcloud app deploy app.yaml
```


## For page autorefresh (delete befor deployment)
<head>
  <meta http-equiv="refresh" content="30">
</head>
