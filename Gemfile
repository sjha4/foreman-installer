source 'https://rubygems.org'

gem 'kafo', '>= 1.0.5'
gem 'librarian-puppet'
gem 'puppet', ENV.key?('PUPPET_VERSION') ? "~> #{ENV['PUPPET_VERSION']}" : '~> 3.0'
gem 'rake'

group :test do
  gem 'rspec'
end