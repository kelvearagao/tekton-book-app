# tekton-lab-app

## Run app locally

```
npm i
npm start
npm run lint
npm run test
```

## Publish app image on Docker

```
docker build -t <USERNAME>/tekton-lab-app .
docker login -u <USERNAME>
docker push <USERNAME>/tekton-lab-app
```

## Deploy app on k8s

```
kubectl apply -f ./deploy.yaml
```
