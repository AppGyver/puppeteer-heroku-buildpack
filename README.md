# puppeteer-heroku-buildpack

Installs dependencies needed in order to run puppeteer on heroku. Be sure to include `{ args: ['--no-sandbox'] }` in your call to `puppeteer.launch`

## Usage

Or use the source code in this repository:

```sh-session
$ heroku buildpacks:set https://github.com/AppGyver/puppeteer-heroku-buildpack.git
```
