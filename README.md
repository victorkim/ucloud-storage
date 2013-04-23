# UcloudStorage

Simple API for ucloud storage

## Installation

Add this line to your application's Gemfile:

    gem 'ucloud_storage'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install ucloud_storage

## Usage

		ucloud = UcloudStorage.new
		ucloud.user = "email"
		ucloud.pass = "API KEY"
		ucloud.authoize
		ucloud.upload(filepath, boxname, destination)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request