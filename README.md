# Asmaa

This is a simple `ruby` gem to detect any Arabian name gender.

Now I have a database of `2434 names` for a starting but I am looking for your contributions.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'asmaa'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install asmaa

## Usage

Just start using it

    Asmaa.get_gender "مراد" # returns "male"
    Asmaa.is_male? "مراد"   # returns true
    Asmaa.is_female? "مراد" # returns false
    
## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

To add more names please add it to the `names.csv` file not to the binary `names.db` file and I will add them to the `db` file in the next version.

## Contributing

Bug reports and pull requests are welcome on GitHub.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

