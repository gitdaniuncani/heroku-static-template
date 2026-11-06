# heroku-static-template

Template for hosting a single-file HTML app on Heroku (internal/private space).

1. Click **Use this template**, then overwrite `index.html` with your HTML.
2. `heroku create <name> --space se-amer-tmt-internal --team se-amer-tmt`
3. `git push heroku main` (or connect the repo on the app's Deploy tab).

`package.json` + `Procfile` make Heroku detect the Node buildpack and serve the folder with `serve` on `$PORT`.
