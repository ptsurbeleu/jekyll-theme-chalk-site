## Understanding gem-based themes

With gem-based themes, some of the site's directories (such as the `_assets`, `_layouts`, `_includes`, and `_sass` directories) are stored in the theme's gem, hidden from your immediate view. Yet all of the necessary directories will be read and processed during Jekyll's build process.

## Prerequisites

If you haven't installed the following tools then go ahead and do so (make sure you have [Homebrew](https://brew.sh/) installed):

    brew install ruby
    brew install npm

On windows, install Ruby and Node with the installers found here:

  - [Ruby](https://rubyinstaller.org/)
  - [Node.js](https://nodejs.org/en/download/)

## Usage

This site has been manually scaffolded and has only files/folders you need to get it up & running.

If you haven't cloned this repository yet then go ahead and clone it:

```
git clone https://github.com/ptsurbeleu/jekyll-theme-chalk-site.git
```

After cloning the repository, go to `jekyll-theme-chalk-site` folder and execute:

```
bundle install -j12
```

This installs all the necessary dependencies for this Jekyll site to work properly. Once this is done
you should see in your terminal something like this:

```
...
Fetching jekyll-theme-chalk 0.1.1
Installing jekyll-theme-chalk 0.1.1
Bundle complete! 3 Gemfile dependencies, 40 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
```

The last step is get Jekyll site up and running with the following command:

```
bundle exec jekyll serve
```

And you are done!

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/ptsurbeleu/jekyll-theme-chalk. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.