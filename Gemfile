source 'https://rubygems.org'

ruby '>= 3.4.0'

ar_version = ENV.fetch('ACTIVERECORD_VERSION', '>= 7.2')
gem 'activerecord', ar_version, '< 9.0', require: false
gem 'rake', require: false

group :development do
  gem 'bump'
  gem 'yard', require: false
end

group :development, :test do
  gem 'debug'
  gem 'rspec', require: false
  gem 'rubocop', '~> 1.12.0', require: false
  gem 'rubocop-rake', require: false
  gem 'rubocop-rspec', '~> 2.2.0', require: false
  gem 'simplecov', require: false
end

group :test do
  gem 'files', require: false
  gem 'git', require: false
  gem 'sqlite3'
end
