source 'http://rubygems.org'

gem 'bundler'
gem 'rake', '~> 0.8.7'
gem 'rails', '~> 3.0.7'

gem 'sqlite3'
gem 'omniauth', '>= 0.2.6'

group :development do
  gem 'capistrano'
end

group :test do
  gem 'rspec-rails', '~> 2.4'
  gem 'capybara', :git => 'git://github.com/jnicklas/capybara.git'
  gem 'launchy'
  gem 'database_cleaner'
  gem 'guard'
  gem 'guard-rspec'
  if RUBY_PLATFORM =~ /Darwin/i
    gem 'rb-fsevent'
    gem 'growl'
  end
end
