# simpleflask

Just make sure you:

1. have the requirements.txt
2. the main python app is using app.py as filename
3. it is listening to 0.0.0.0 port 8080


Just perform the following:  
```
oc new-project simpleflask
oc new-app python~https://github.com/itsbanjo/simpleflask
oc expose svc/simplefask
oc get route
```
