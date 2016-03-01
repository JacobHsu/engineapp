# google-api

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