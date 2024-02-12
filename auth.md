From your GitHub account, go to Settings → Developer Settings → Personal Access Token → Generate New Token (Give your password) → Fillup the form → click Generate token → Copy the generated Token, it will be something like ghp_sFhFsSHhTKAKaj3RLjmks4Tzuzgthdvfsrta

### For a Linux-based OS 
For Linux, you need to configure the local GIT client with a username and email address,

```
$ git config --global credential.helper store (it will store the credentials on the machine in plain text, has security concerns)
(can later use $git config -l to get the token/password)

$ git config --global user.name "your_github_username"
$ git config --global user.email "your_github_email"
$ git config -l
Once GIT is configured, we can begin using it to access GitHub. Example:

$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `YOUR-REPOSITORY`...
Username: <type your username>
Password: <type your password or personal access token (GitHub)
```

### For Windows OS 
Go to Credential Manager from Control Panel → Windows Credentials → find git:https://github.com → Edit → On Password replace with with your GitHub Personal Access Token → You are Done
