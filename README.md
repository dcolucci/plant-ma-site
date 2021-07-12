# Plant Ma Front End

A static site for Plant Ma content, powered by [Jekyll](https://jekyllrb.com).

## Local dev

Make sure you are using the required version of Ruby: **2.6 or above**
```sh
$ rvm use 2.6
```

Install dependencies
```sh
$ bundle install
```

> If you have problems with `bundle install`, [this page might provide some tips](https://bundler.io/blog/2019/05/14/solutions-for-cant-find-gem-bundler-with-executable-bundle.html).

Start server
```sh
$ bundle exec jekyll serve
```

## Deployment

The site is currently deployed using AWS Amplify. Any changes pushed to `master` will be automatically deployed to www.agathaisabel.com.
