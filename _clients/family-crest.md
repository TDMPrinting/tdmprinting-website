---
name: Edition Template
subtitle: Product documentation template for Jekyll
external_url: 'https://github.com/CloudCannon/edition-jekyll-template'
image_path: /images/clients/edition.png
---


3D artists can bring their content off the screen and onto their desks.

## Features

* Two column layout
* Full text search
* Pre-styled components
* Auto-generated navigation based on category
* Optimised for editing in [CloudCannon](http://cloudcannon.com/)
* Change log
* RSS/Atom feed
* SEO tags
* Google Analytics

## Setup

1. Add your site and author details in `_config.yml`{: .highlighter-rouge}.
2. Get a workflow going to see your site’s output (with [CloudCannon](https://app.cloudcannon.com/) or Jekyll locally).

## Develop

Edition was built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

<div class="language-bash highlighter-rouge"><pre class="highlight"><code><span class="gp">$ </span>bundle install
</code></pre></div>

Run `jekyll`{: .highlighter-rouge} commands through Bundler to ensure you’re using the right versions:

<div class="language-bash highlighter-rouge"><pre class="highlight"><code><span class="gp">$ </span>bundle <span class="nb">exec </span>jekyll serve
</code></pre></div>

## Editing

Edition is already optimised for adding, updating and removing documentation pages in CloudCannon.

### Documentation pages

* Add, update or remove a documentation page in the *Documentation* collection.
* Change the category of a documentation page to move it to another section in the navigation.
* Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs`{: .highlighter-rouge} folder.

### Change log

* Add, update or remove change log entries from your posts.
* Tag entries as minor or major in the front matter.

### Search

* Add `excluded_in_search: true`{: .highlighter-rouge} to any documentation page’s front matter to exclude that page in the search results.

### Navigation

* Change `site.show_full_navigation`{: .highlighter-rouge} to control all or only the current navigation group being open.