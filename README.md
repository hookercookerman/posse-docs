# posse-docs


### Clone All Repos

```zsh
curl -s https://$GITHUB_AT:@api.github.com/orgs/connectedcars/repos?per_page=200 | jq .[].ssh_url | xargs -n 1 git clone
```
