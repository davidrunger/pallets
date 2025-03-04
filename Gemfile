source 'https://rubygems.org'

gemspec

gem 'rake'

group :test do
  gem 'rspec'
end

group :development, :test do
  # Go back to upstream if/when https://github.com/deivid-rodriguez/pry-byebug/pull/ 428 is merged.
  gem 'pry-byebug', require: false, github: 'davidrunger/pry-byebug'
  # Time travel in style
  gem 'timecop'
end
