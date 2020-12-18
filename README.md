# lunatech-blog
Contains our blog in Asciidoctor format.

Each post is localted in the `posts` directory with the following format: `yyyy-MM-dd-title.asciidoc`

In the `media` directory there should be a matching image named `yyyy-MM-dd-title/background.png`

All media used in the posts should be located in the `media` directory under a `yyyy-MM-dd-title` directory ie `media/yyy-MM-dd-title`

To add you blog post:
* Install giter8 `brew install giter8`
* Fork this repo
* Checkout the forked repo
* In the repo directory `g8 file://.`
* Write your blog post
* Submit a pull request

# Information regarding giter8

If you see this error :

  Error: giter8 has been disabled because it fetches unversioned dependencies at runtime!
  
Then you can bypass the warning message as follow

  brew edit giter8
  
and delete this line  
  disable! because: "fetches unversioned dependencies at runtime"
  
then run brew install giter8 again

