#mobilevis.github.io

##Configuring site properties

Site metadata is in [_config.yml](_config.yml)

##Editing the index and about pages

You can edit the [index.md](index.md) amd [about.md](about.md) pages here and changes will be reflected on [mobilevis.github.io](https://mobilevis.github.io/).

##Adding posts

Add posts in .md format to the [_posts](master/_posts) directory. Posts should be named following the `YYYY-MM-DD-post-title.md` convention.

##Editing the style

Change the style in [assets/main.scss](assets/main.scss).

##Adding images and other assets

Add images to [assets](assets/). You can also add remote iframe content to a page or post by directly inserting an `<iframe />` tag.

##Local editing

To edit the site remotely, open a terminal where you want to work locally and follow these instructions:

0. Ensure that git and ruby are installed.
1. Clone the repository: `git clone https://github.com/mobilevis/mobilevis.github.io.git` and `cd mobilevis.github.io.git`.
2. Install bundler: `gem install bundler`.
3. Install the bundle: `bundle install`; Update as needed: `bundle update`.
4. Run locally at [localhost:4000](http://localhost:4000/): `bundle exec jekyll serve`
5. Make edits to the site (see above)
6. Add, commit, and push your changes: `git add *`, `git commit -m 'your commit message'`, `git push`.