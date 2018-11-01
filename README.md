# charts
Vamp.io kubernetes charts repository

Add this repo to Helm:
```
$ helm repo add vamp https://magneticio.github.io/charts 
$ helm repo list
```
NAME            URL                                        
vamp    https://magneticio.github.io/charts

Now check it by creating a new deploy from the repo:
```
$ helm install vamp/lifter --name=lifter
```
