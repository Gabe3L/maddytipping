# Maddy Tipping's English Website

## Description

...

#### Gallery

To add to the gallery, go to the file: `_data/gallery.yml` and add the following structure:

```
photos:
  - url: path/to/your/photo.png
    description: Alt for the image
    quote: text on hover
```

## Install

This guide assumes you have already installed Ruby, and navigated into a local copy of the GitHub repository.

First, install bundler:
```bash
gem install bundler
```

Next, install Jekyll:
```bash
gem install jekyll
```

Then, install every other dependancy:
```bash
bundle install
```

Lastly, boot the website:
```bash
bundle exec jekyll serve --livereload
```

## License

This project is avaiable under the [GNU General Public License](LICENSE.txt) and the project theme is available as open source under the terms of the [MIT License](THEME-LICENSE.txt).