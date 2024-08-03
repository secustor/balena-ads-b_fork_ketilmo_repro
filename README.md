# 30425

Reproduction for [Renovate discussion 30425](https://github.com/renovatebot/renovate/discussions/30425).

## Current behavior

Renovate can't find the new versions

```yaml
INFO: Found no results from datasource that look like a version
{
  "dependency": "fr24feed"
  "result": {
    "releases": []
  }
}
```

## Expected behavior

### Commit hash pinning disabled

Renovate can find the versions
