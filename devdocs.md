## How to publish on npm

* Update the version in projects/plotly/package.json
* Update the CHANGELOG.md
* `ng test --codeCoverage=true --progress=true --watch=false`
* `cp README.md angular-plotly.png projects/plotly`
* `ng build plotly --prod`
* `cd dist/plotly`
* `npm publish`
* `git tag -a <version> -m <version>`
* `git push --tags`
