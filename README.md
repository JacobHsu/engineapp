# Docs

https://cloud.google.com/appengine/docs/php/  

Before getting started, be sure to download the [PHP SDK for App Engine](https://cloud.google.com/appengine/downloads#Google_App_Engine_SDK_for_PHP).


Create a new repository on GitHub. To avoid errors, do not initialize the new repository with README  

Google App Engine Launcher  
File/Create New Application  

Change the current working directory to your local project.  
`$cd engineapp`  

Initialize the local directory as a Git repository.  
`$git init`  


.git config  

add
```
[remote "origin"]
    url = git@github.com:JacobHsu/engineapp.git
    fetch = +refs/heads/*:refs/remotes/origin/*
    puttykeyfile = C:\\Git\\yourkey.ppk
[branch "master"]
    remote = origin
    merge = refs/heads/master
```

`$git add`  
`$git commit -m "First commit"`  
`$git push origin master`  

# Google Console

https://console.cloud.google.com/project
add Project

* engineapp  <your-app-id>


fix app.yaml
```
application: <your-app-id>
version: 1
runtime: php55
```

Google App Engine Launcher  
Deploy  

The full URL for your application is http://your-app-id.appspot.com/.
