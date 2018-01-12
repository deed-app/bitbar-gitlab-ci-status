# BitBar GitLab CI Status

![BitBar GitLab CI](https://raw.githubusercontent.com/deed-app/bitbar-gitlab-ci-status/master/presentation.jpg)

---

This simple plugins pulls the last CI pipeline of your project and displays it's status in your task bar.
Uses the GitLab REST API.

## Dependencies

This plugins needs `jq`.

Fetch it from 
https://stedolan.github.io/jq/

or just 

```
brew install js
```

## Configuration

Open the ```gitlab-ci-status.5s.sh``` script and change the following:

```
GITLAB_HOSTNAME="https://your-gitlab-.com"
GITLAB_API_TOKEN="YOUR_TOKEN"
GITLAB_PROJECT_ID="1"
```