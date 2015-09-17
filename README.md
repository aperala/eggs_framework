# EggsFramework

## Installation

Add this line to your application's Gemfile:

gem 'eggs_framework', :git => 'https://github.com/aperala/eggs_framework.git'

And then execute:

  $ bundle

## Usage

TODO: This framework is built around a 6-column grid with a horizontal navbar. The background and navbar colors are set by giving the body the class "speckled-egg-theme" and setting the default-main-color in _variables.scss. Default font: Google Fonts Josefin Sans.

Create a rounded button with '@include rounded-button(radius in px)'. 

Create a vertically centered element with '@include vertically-centered-element'. 

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/eggs_framework. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

