Source code for the professional website for Christopher Tull. 

Please visit my site at [christophertull.org](http://christophertull.org)

This code os modified from work by [Stuart Geiger](https://github.com/staeiou). See more info at https://academicpages.github.io/

## To run locally (not on GitHub Pages, to serve on your own computer)
1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll serve` to generate the HTML and serve it from localhost:4000

