
Hyde Press Bookshelf - [`hydepress.github.io`](http://hydepress.github.io)


### Build Notes

For local build use the github-pages gem with bundler:

    $ bundle exec jekyll build --safe  # or
    $ bundle exec jekyll b --safe
   

#### Git Submodules

To add use:

    $ git submodule add https://github.com/hydepress/jekyll _jekyll

To check try:

    $ cat .gitmodules
   
Printing something like:

    [submodule "_jekyll"]
        path = _jekyll
        url = https://github.com/hydepress/jekyll


Todo: Add/use  --name jekyll option to keep original name - why? why not?

Update Submodule.  Follow these steps:

to be done
