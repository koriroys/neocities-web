neocities-web
=============

Web interface for neocities.org

# Instructions for running locally (OSX)

assumes you have bundler and postgres installed

```
bundle install
brew install libmagic
cp config.yml{.template,}
createdb neocities
bundle exec rackup
```
