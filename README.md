# Junyan Yu — Personal Academic Website

This repository contains the source for Junyan Yu's (俞俊言) personal academic website, presenting his academic background, research interests, and academic activities. The site is built with Jekyll and hosted on GitHub Pages.

**Website:** [https://junyanyu2005.github.io/](https://junyanyu2005.github.io/)

## Run locally

Install Git, Ruby, Bundler, and Node.js, then run:

```bash
git clone https://github.com/JunyanYu2005/JunyanYu2005.github.io.git
cd JunyanYu2005.github.io
bundle install
bundle exec jekyll serve -l -H localhost
```

Open [http://localhost:4000](http://localhost:4000) to preview the site. Jekyll rebuilds the site when content changes; restart the server after changing `_config.yml`.

If Bundler reports a permissions error, install dependencies inside the repository:

```bash
bundle config set --local path 'vendor/bundle'
bundle install
```

On Linux, Ruby development headers and build tools may also be required (`ruby-dev`, `build-essential`, `gcc`, and `make`).

## Credits and license

This website is based on [Academic Pages](https://github.com/academicpages/academicpages.github.io), originally forked and adapted by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/).

The underlying theme is © 2016 Michael Rose and released under the MIT License. See [LICENSE](LICENSE) for the license text and copyright notice.
