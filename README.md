# dfisher95350.github.io

View this site at [https://dfisher95350.github.io/](https://dfisher95350.github.io/).

## How-to

For detailed how-to documentation, see our `ruby/rb-jekyll` project.

A brief quick-start (presuming `ruby`, `gem`, and `bundle`) ...

### Step 1

We'll need a `.bundle/config` file _that we don't commit_.

```shell
bundle config set --local path 'vendor/bundle'
```

### Step 2

Install gems per `Gemfile` (into `vendor/bundle`).

```shell
bundle install
```

### Step 3

Generate `_site_` and serve.

```shell
bundle exec jekyll serve
```

Notice ...

```shell
Configuration file: /mnt/i/opt/my/shared/projects/dfisher95350.github.io/_config.yml
            Source: /mnt/i/opt/my/shared/projects/dfisher95350.github.io
       Destination: /mnt/i/opt/my/shared/projects/dfisher95350.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
 Auto-regeneration: enabled for '/mnt/i/opt/my/shared/projects/dfisher95350.github.io'
    Server address: http://127.0.0.1:4000
  Server running... press ctrl-c to stop.
```

Now we can point our Web browser to [http://127.0.0.1:4000](http://127.0.0.1:4000).