Uses [Jekyll](https://jekyllrb.com/) hosted on [GitHub Pages](https://pages.github.com/)

# Getting Started

Ruby and rubygems already installed:

    gem install bundler
    bundle

# Development 

To start a local server: `jekyll serve`

# Deploying

    ./script/deploy.sh

https://content.nathanorick.com/weddings/sample/

# Editing pages/how it's laid out
## Pages
These are very strangely built... all the info for the pages is in the files under /_data, but the formatting is done in the files under /_includes 

### Edits:
- I moved pages I didn't want into the "optional pages" folder
- God... evidently something weird must have happened when I did that, so I actually kept unwanted pages and jsut removed them from the nav bar. You can still manually navigate to them though (ex. url/celebrations)

## Color scheme
under _data/settings.yml, theme, can make changes

## Photos
### Banner photos
Found under assets/img/

I just replaced images and named them the same thing because I didn't want to bother finding paths in different files. Hence, bear photo is name flowers.jpg or whatever. Idk why the details image is broken