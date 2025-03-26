source 'https://rubygems.org'

gemspec

gem 'rake'

group :test do
  gem 'rspec'
end

group :development, :test do
  gem 'pry-byebug', require: false, github: 'davidrunger/pry-byebug'
  # Time travel in style
  gem 'timecop'
end
