# Offline Application Service Workshop

## Just cf push

The content in this workshop is already generated. Just clone this repo and `cf push` is all that's needed.

For build instructions (for modification or adopting to your needs), see below.

## Building

To generate this workshop you'll need [Hugo](https://gohugo.io/) installed. 

Once that's installed cd into the root of the project and run this:

```
git submodule add https://github.com/alex-shpak/hugo-book themes/book
```

Then to use the live server on [http://localhost:1313](http://localhost:1313)
```
hugo server
```

To generate HTML output
```
hugo
```

This is set up to push to Cloud Foundry. (Just make sure to change any properties as necessary)
```
cf push
```

