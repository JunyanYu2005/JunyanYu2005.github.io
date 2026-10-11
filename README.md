# Junyan Yu's Personal Homepage

This repository contains the source code for my personal academic website, hosted at https://junyanyu2005.github.io.

The site is built with Jekyll and customized from the Academic Pages template to present my academic profile, research interests, publications, and related work.

## About

I am Junyan Yu, a junior undergraduate student at The Chinese University of Hong Kong. I major in Chinese Language and Literature and minor in Linguistics.

My academic interests center on Chinese dialect grammar, syntax, and semantics. I am especially interested in how grammatical patterns in regional varieties illuminate broader theoretical questions in linguistics.

## Website Highlights

- Academic profile and background
- Research interests and intellectual focus
- Publications and talks
- Curriculum vitae and project highlights
- Personal reflection on language, culture, and scholarship

## Local Development

To preview the site locally, install the required dependencies and run Jekyll:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open `http://localhost:4000` in your browser.

### Using a different IDE

1. Make sure you have `ruby-dev`, `bundler`, and `nodejs` installed.
2. On most Linux distributions and [Windows Subsystem Linux](https://learn.microsoft.com/en-us/windows/wsl/about), run:

```bash
sudo apt install ruby-dev ruby-bundler nodejs
```

If you see an error about missing packages, update apt first and retry:

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install ruby-dev ruby-bundler nodejs
```

On macOS:

```bash
brew install ruby
brew install node
gem install bundler
```

3. If you see permission errors while installing gems, install them locally:

```bash
bundle config set --local path 'vendor/bundle'
```

4. Run the local site preview with Jekyll:

```bash
bundle exec jekyll serve -l -H localhost
```

If you are running on Linux, it may also be necessary to install system build tools:

```bash
sudo apt install build-essential gcc make
```

### Additional tutorials

Additional tutorials for working with the Academic Pages template are available here:
- https://jayrobwilliams.com/posts/2020/06/academic-website/

## Project Structure

- `_config.yml` — site settings and profile metadata
- `_pages/` — pages such as About, CV, and other site content
- `_publications/` — publication entries
- `_talks/` — talk entries
- `images/` — profile and homepage assets
- `files/` — downloadable materials

## Notes

This homepage is customized for my personal academic profile and reflects my current research interests and academic direction. The underlying template is based on Academic Pages, but the content and structure have been adapted to fit my own work and identity.

> 無冥冥之志者無昭昭之明，無惛惛之事者無赫赫之功。——《荀子》
