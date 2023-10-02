# Webpage

To deploy, do the following:

1. Build the site:

```r
blogdown::build_site()
```

2. Commit your changes
3. Push the changes to gh-pages

```sh
git subtree push --prefix public origin gh-pages
```