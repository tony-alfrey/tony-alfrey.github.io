# Tony Alfrey memorial site

## Local development

```
$ brew bundle # Install the needed Mac + Homebrew deps

$ ruby-install ruby 2.7.2 # Install the needed Ruby version

$ chruby 2.7.2 # Switch to the needed version

$ ruby --version # Confirm which version is active

$ bundle update --bundler # Use a current version of Bundler

$ bundle install # Install dependencies

$ bundle exec jekyll serve # Start the local dev server

http://localhost:4000 # Visit the local site
```

[This article](https://blog.engineyard.com/how-to-install-ruby-on-a-mac-with-chruby-rbenv-or-rvm) is helpful re: debugging Ruby version issues.

## Misc

Requirements for this site to be auto-published to `tony-alfrey.github.io`:

- The Github org needs to be named: `tony-alfrey`
- The repo name needs to be: `tony-alfrey.github.io`
