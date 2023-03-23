# [WIP] Github Settings actions

## Why
TBD
## How it works

### Add `settings.yml` file in your `.github` repo

```
repository:
  name: setting-demo
  description: This is just a demo test
  private: true
  has_issues: false
  has_projects: true
  has_wiki: true
  has_pages: true
  has_downloads: false
  has_discussions: true
```

### Create a workflow

Check `.github/workflows/apply-settings.yml`


## TODO
- [] Publish as a github workflow
- [] Add more settings 