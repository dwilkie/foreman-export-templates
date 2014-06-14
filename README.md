# Foreman-Export-Templates

A collection of templates for [Foreman](https://github.com/ddollar/foreman)

## Installation

```
mkdir -p ~/.foreman/templates
cd ~/.foreman/templates
git clone git://github.com/dwilkie/foreman-export-templates .
```

## Usage

Example using `rbenv sudo`

```
rbenv sudo bundle exec foreman export upstart /etc/init -u user -a app-name -e .env.production -t ~/.foreman/templates/upstartold
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
