# Newsletter

A newsletter focused [Jekyll](https://jekyllrb.com/) theme originally developed for [Early Often](https://www.earlyoften.com).

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-newsletter"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-newsletter
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-theme-newsletter

## Usage

TODO: Write usage instructions here. Describe your available layouts, includes, and/or sass.

## Contributing

Bug reports and pull requests are welcome on [GitHub](https://github.com/gabor-meszaros/newsletter). This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

In order to contribute to the development of this theme, you'll need a proper development environment. It is recommended to use the [Jekyll workstation](https://github.com/gabor-meszaros/jekyll-workstation) as it is developed by the same person who maintains this theme. Please check the repository for further information.

The good news is that you can test the theme just as it was like a normal Jekyll site! To test your theme, run

    $ bundle exec jekyll serve --watch --host 0.0.0.0 --force_polling --source example

command inside the Jekyll workstation, and open your browser at `http://localhost:4000`. The command will start a Jekyll server that uses this theme. Add pages, documents, data, etc. to the `example` directory like normal to test the theme's contents. As you make modifications to the theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When the theme is released, only the files in `_layouts`, `_includes`, and `_sass` tracked with Git will be released.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
