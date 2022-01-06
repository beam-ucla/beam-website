# BSI Website
Soon to be renamed to BSI!

[![Netlify Status](https://api.netlify.com/api/v1/badges/89e48d91-174d-4ab0-98e2-9d9f53c98ee9/deploy-status)](https://app.netlify.com/sites/confident-engelbart-3f10ae/deploys)

BEAM (Building Engineers and Mentors @ UCLA) is a service club at UCLA that brings hands-on science activities to underserved K-8 schools across Los Angeles. This repository holds the code for our simple website, which hosts logistics information and our lesson plans.

## Development Setup

Making your own changes is easy! This website uses [Jekyll](https://jekyllrb.com), a ruby-based static site generator, to do lots of the boring work - that way, you can focus on changing the content!

To get a copy of this website running locally on your machine, you'll need [Ruby](https://www.ruby-lang.org/en/), a copy of this repo, and access to your system's shell/terminal.

*Note:* we recommend using [rvm](https://rvm.io/) instead of your system ruby; it makes life easier :smile:!

First, let's install [Bundler](https://bundler.io/), a gem environment manager for ruby. Type this anywhere in your shell:

```bash
$ gem install bundler
...
```

Then, we can clone our project and install its dependencies.

```bash
$ git clone https://github.com/mattxwang/beam-website.git
...
$ cd beam-website
$ bundle
...
```

This should install all of our RubyGems dependencies! Note that we've committed a `Gemfile.lock`, so you should get a working set of gems.

Finally, run:

```bash

$ bundle exec jekyll serve
Configuration file: /Users/mattxwang/code/beam-website/_config.yml
            Source: /Users/mattxwang/code/beam-website
       Destination: /Users/mattxwang/code/beam-website/_site
 Incremental build: disabled. Enable with --incremental
      Generating... 
                    done in 0.348 seconds.
 Auto-regeneration: enabled for '/Users/mattxwang/code/beam-website'
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.

```

Visit whatever follows the server address line in your browser, which is usually [http://127.0.0.1:4000/](http://127.0.0.1:4000/).

If you run into any issues, please let us know on our [issues tracker](https://github.com/mattxwang/beam-website).


# How to Use

> NOTE: GitHub Actions is required to deploy to GitHub Pages because GitHub [refuses to update their version of Jekyll](https://github.com/github/pages-gem/issues/651).

# Credits

This Jekyll theme was made by Andrew Banchich, based on the Forty theme by HTML5 UP.
The original repo is found here: https://github.com/andrewbanchich/forty-jekyll-theme

Original Credits from HTML5 UP:

```

Credits:

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other:
		jQuery (jquery.com)
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		background-size polyfill (github.com/louisremi)
		Misc. Sass functions (@HugoGiraudel)
		Respond.js (j.mp/respondjs)
		Skel (skel.io)
```

Repository [Jekyll logo](https://github.com/jekyll/brand) icon licensed under a [Creative Commons Attribution 4.0 Intb;;ernational License](http://choosealicense.com/licenses/cc-by-4.0/).
b;;
