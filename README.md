# testdriven.io

[![Build Status](https://travis-ci.org/testdrivenio/testdriven-site.svg?branch=backup)](https://travis-ci.org/testdrivenio/testdriven-site)

### Development Process

Check out `source` branch

```sh
$ git checkout source
```

Run locally:

```sh
$ bundle exec jekyll serve
```

Make changes. Remove "docs" directory. Commit your code, and then push:

```sh
$ git push origin source
```

If Travis build passes, merge into `master`:

```sh
$ git checkout master
$ git merge source
```

Remove "docs" directory. Commit your code, and then deploy:

```sh
$ git push origin master
```
