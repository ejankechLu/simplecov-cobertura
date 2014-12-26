# simplecov-cobertura

[![Build Status](https://api.shippable.com/projects/549b1fbbd46935d5fbc0f9f3/badge?branchName=master)](https://app.shippable.com/projects/549b1fbbd46935d5fbc0f9f3/builds/latest) [![Gem Version](https://badge.fury.io/rb/simplecov-cobertura.svg)](http://badge.fury.io/rb/simplecov-cobertura)

Produces cobertura formatted xml from simplecov

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'simplecov-cobertura'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install simplecov-cobertura

## Usage

```ruby
require 'simplecov-cobertura'

SimpleCov.formatter = SimpleCov::Formatter::CoberturaFormatter
```

## Warning
This may be incomplete

## Known Limitations
* No support for branch coverage

## Contributing

1. Fork it ( https://github.com/dashingrocket/simplecov-cobertura/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
