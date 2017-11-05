# Setup
See [here](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/) for more information about running lennaerts.me locally for testing.

1. `rbenv global 2.4.2` to make sure you're not on system since you can't install gems to system's gem directory.
2. If bundler is not already installed run `gem install bundler`.
3. In project root directory run `bundle install`. This uses the Gemfile to install the necessary dependencies.
4. `bundle exec jekyll serve` to start server
5. Done :thumbsup:

# TODO
* Head includes 3 fonts. Headings: Raleway. Body: Merriweather. Code: Fira Mono
* Head includes fontawesome for social icons