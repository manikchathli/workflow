# Workflow

Setup secrets in Settings --> Secrets

```text
GH_TOKEN :- Your github personal access token, from https://github.com/settings/tokens
MIRROR_REPOSLUG :- Your Secret Repository, as in "<username>/<reponame>"
```

Then edit .github/workflows/*.yml

Change `GitHubMail` and `GitHubName` environment variable as your own

And That's it.
