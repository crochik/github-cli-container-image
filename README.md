# github-cli-container-image

Simple alpine image with git and github client

## How to use

You can generate a Github token and assign to the `GITHUB_TOKEN` environment variable so it will be used by the github cli.

To use the token to access git repositories in github (as long as the token gives you access to it):

```
gh auth setup-git
```

Before trying to commit any code make sure that you have defined the user name and email:

```
git config --global user.email "your_email@domain.com"
git config --global user.name "Your Name"
```
