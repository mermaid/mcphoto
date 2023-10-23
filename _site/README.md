# Ink

Ink is a minmal two-column theme for [Jekyll](http://jekyllrb.com) 

![Screenshot](https://s32.postimg.org/gdtp6pw1x/ink.png)

# Installation 

## run
`docker-compose up` to run the jekyll build
`yarn tinacms build && docker-compose up` to run the tinacms & jekyll build

##### Setup on your local machine
 * Clone or download the repository
 * You should have [ruby](https://www.ruby-lang.org/en/) installed in your system
 * Install ruby using `rbenv` and homebrew
   * `brew install rbenv ruby-build`
   * `rbenv install 2.6.3`
   * `rbenv global 2.6.3`
 * Install bundler & jekyll which helps in specifying and installing dependencies of any Ruby project ```gem install bundler jekyl```
 * Go to the root of the repo and run this - ```bundle install```
 * Then - ```bundle exec jekyll serve```

##### Useful Commands
 * Resize images based on the long side
   * `sips -Z 640 *.jpg`

# Configuration 
 * Change the following in ```_config.yml```
 ```
    name:               "Ink"
    description:        "A minimalistic jekyll theme for humans"
    url:                ""
    author:             "thinker3197"
    email:              "jhondoe@abc.com"
    gravatar_hash:      "205e460b479e2e5b48aec07710c08d50"
    twitter:            "jhondoe"
    email:              "jhondoe@abc.com"
    github:             "jhondoe"
    pinterest:          "jhondoe"
    linkedin:           "jhondoe"
    facebook:           "jhondoe"
    
 ```
 * Set the number of posts that appear in each page by changing the ```paginate``` option in ```_config.yml``` file. Default value is 5.
 * Add more navigation menus in the ```nav``` section in ```_config.yml```. 
 * Add your custom url in ```url``` option. Example : http://thinker3197.github.io/blog. Consult the ```gh-pages``` branch to see the basic setup for a blog.
 * Add your custom background by adding a custom background link in the ```background``` option in ```_config.yml```.
 
# Licensce

Open sourced under [MIT LICENSE](https://github.com/thinker3197/ink/blob/master/LICENSE) 





# mcphoto
