## SetUp 
The Jekyll Version used is **4.2.1**.

After [Installation](https://jekyllrb.com/docs/installation/), execute:
```
bundle exec jekyll serve --livereload
```

## Check Links, Html, etc
```
bundle exec htmlproofer --allow_hash_href --empty_alt_ignore --assume_extension --disable_external ./_site
```