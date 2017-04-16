# ACSS site

This is the repo for the Aston Computer Science Society website. It's a Jekyll-generated static site, running on GitHub pages.

## Getting set up

First up, you'll want to fork this repository on GitHub. This creates your own version which you can modify however you like. Any changes you make will have to be merged back into this version, which we'll discuss a little bit [further down](#contributing).

### Running locally

You'll need to have Ruby installed, along with bundler. Then run `bundle install` to fetch all the dependencies. TODO: add better instructions here.

You can then run `bundle exec jekyll serve` and open up the URL it shows.

### Writing blog posts

Posts are located in the `_posts` directory. To create a new one, simply create a file with a name in the format `YYYY-MM-DD-name-of-post.md` and add the Jekyll 'front-matter' (the comment at the top of the file). For an example, see existing blog posts. It might just be worth copying the contents of an existing post to get started with.

## Contributing

Changes to the site can come in many forms, ranging from fixes to new content. We're particularly keen on having blog posts written by society members. If you're interested in this, please do speak to a committee member first!

Once you've made changes to your fork of the repository, you'll most likely want to merge them back into the main repository (and make them live on the actual ACSS site). To do this, you'll need to create a pull request on GitHub. This is effectively a request for your changes to be added to the original version.

In the pull request, provide as much info as possible about what you changed and why. Most likely after a bit of discussion, and if it all looks good, we'll accept the pull request, and you changes will be made live! You'll also now be listed as a contributor on GitHub 😎.
