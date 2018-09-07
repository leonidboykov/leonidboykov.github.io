# Github Pages redirects

This repo contains Jekyll-based files with redirects to the main Netlify static-site [deployment](https://leonidboykov.com).

## Adding redirects

To redirect a Github Pages project `project_name` to a `https://new_url/`, just add a `project_name.md` file with the following content

```markdown
---
redirect_to: https://new_url/
---
```
