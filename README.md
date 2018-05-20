# Artenes' personal website

My personal web site to showcase my portfolio and other informations about my career as a developer engineer.

# Quick start

This site is made with Hugo, so to install it go to the [Hugo releases page](https://github.com/gohugoio/hugo/releases). Don't forget to add it to your PATH.

Then clone the repo:

```
git clone git@github.com:Artenes/artenes.github.io.git
```

Checkout the `source` branch and initialize the submodules (repo theme and repo where static files go). This is the branch where all the source files are:

```
git checkout source
git submodule update --init
```

To see the site in the browser run:

```
hugo serve
```

And access your browser in [http://localhost:1313/](http://localhost:1313/)

To deploy the site, run the script that it is in the root of this repository (int the source branch):

```
chmod +x ./deploy.sh && ./deploy.sh
```

The script will run `hugo` to build the site and will push the generated files to the `master` branch of this repo. After that, wait a couple of minutes and go checkout out [artenes.github.io](http://artenes.github.io/)