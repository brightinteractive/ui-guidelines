# ui-guidelines


UI guidelines is a public site hosted by github-pages using Jeckyll.

Running the site locally


Prerequisites

Ruby
Jekyll requires at least version <kbd>2.0.0</kbd> of Ruby. If you are on a mac

Bundler
Bundler is a package manager that makes versioning Ruby software like Jekyll a lot easier if you're going to be building GitHub Pages sites locally. If you don't already have Bundler installed, you can install it by running the command gem install bundler.

Jekyll
To install the version of Jekyll that aligns with that used by github pages, go to the root of this repo and run:
	bundle install


Running Jekyll

To run Jekyll in a way that matches the GitHub Pages build server, run Jekyll with Bundler:

	bundle exec jekyll serve

Then your site should be available at <a href="http://localhost:4000" target="_blank">http://localhost:4000</a>


It will also watch for any changes and regenerate the site automatically.
