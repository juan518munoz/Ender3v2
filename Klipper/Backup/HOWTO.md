# Tutorial
Follow the guide [here](https://klipperbackup.xyz/installation/#run-installation).

Note for creating a github token: 
```
One small security tip: The personal access token (PAT) you created can be used to make changes to any of your repositories. To fix this, when you create the PAT, there is an option there "Fine-grained tokens". Select that option. When creating the token, for "Repository Access" choose "Only select repositories", and then add the repository you just created for the backups. For permissions, expand the "Repository permissions" section and grant read and write permission for "Contents". Those are the only permissions that the script needs.  Also, when you're editing the .env value,  you can create the setting "commit_username=xxxx", and set xxxx to any value you want (doesn't have to be any kind of user you create). This will just make commits from the script show up under that name. This is useful to distinguish commits from the script from any commits you make yourself.
```

