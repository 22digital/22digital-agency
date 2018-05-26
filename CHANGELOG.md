# Change-Log for 22digital.agency

Below is a detailed change-log, along with specific tasks completed, for each
version released to date for 22digital.agency.

___By the way, this should not have taken as long to set  up as it has/did.___

## Version 0.3.4 (26/05/2018)

- [#enhancement](#enhancement)
  - Minor update to the README.md file.

## Version 0.3.3 (26/05/2018)

- [#enhancement](#enhancement)
  - Updated `README.md` to reflect Heroku and not gh-pages.
  - Deleted the `CNAME` file as this is only used on gh-pages.

## Version 0.3.2 (26/05/2018)

- [#bugfix](#bugfix)
  - Updated the `index.md` file to redirect to `https://22digital.co.za`
- [#new](#new)
  - Added `Procfile` back with this command:
    `bundle exec rackup config.ru -p $PORT`

## Version 0.3.1 (26/05/2018)

- [#enhancement](#enhancement)
  - Tweaking Procfile to get site loaded.
  - Added new gem information in the `Gemfile`.
  - Changing `Procfile` to run `bundle install` before trying to run Jekyll.
  - Ignoring some files in the `_config.yml` file.
  - Updated `bundler` to version `1.16.1` from `1.15.2` (I hope anyway).
- [#new](#new)
  - Removed `Procfile` completely.
  - Added a `config.ru` file to get it to run.

## Version 0.3.0 (25/05/2018)

- [#new](#new)
  - Activated Heroku app at `https://agency-22digital.herokuapp.com/` with
    a new `Procfile`.
- [#enhancement](#enhancement)
  - Updating Gemfile for use with Heroku.

## Version 0.2.0 (25/05/2018)

This version isn't functioning. I'm ditching GitHub Pages and moving this to
Heroku. I cannot figure out what is happening with GitHub Pages and why it
won't load `22digital.agency` at all. It works on my localhost but not
in a live, production environment. The next release will be operational
on Heroku.

- [#new](#new)
  - Activated GitHub Pages website.
  - Added `CNAME` for the GitHub Pages setup.
  - Added `_config.yml` to setup a Jekyll site.
  - Added `Gemfile` to load the gems required for Jekyll & Github Pages.
- [#enhancement](#enhancement)
  - Updated `README.md` to clean it up.
  - The `.gitignore` file has been updated for new folders.
- [#bugfix](#bugfix)
  - Trying to get the site to work under `gh-pages` branch.
  - Fixed a bug where the site was inaccessible.

## Version 0.1.0 (25/05/2018)

- [#new](#new)
  - Added `.htaccess` file to force a redirect.
- [#enhancement](#enhancement)
  - Updated the following files with correct info:
    - `CHANGELOG.md`
    - `CODE_OF_CONDUCT.md`
    - `CONTRIBUTING.md`
    - `README.md`

## Version 0.0.2 (25/05/2018)

- [#enhancement](#enhancement)
  - Basic git and GitHub file structure put in place. Using the
    @justinhartman/.github project as template files.

## Version 0.0.1 (25/05/2018)

- [#new](#new)
  - Initial Release
