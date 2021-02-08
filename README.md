# ecoidx_report
Example of using ecoidx in a bookdown, editable as a Google Doc


## Developer

### Automatically compile website via Netlify

* [Deploy your bookdown project to Netlify with Github Actions | Emil Hvitfeldt](https://www.hvitfeldt.me/blog/bookdown-netlify-github-actions/)


### Rmarkdown <-> Google Docs

Added in _output.yml:

```yaml
bookdown::word_document2:
  toc: true
```

