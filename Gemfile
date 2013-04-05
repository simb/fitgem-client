source 'http://rubygems.org'

gem 'rails', '~> 3.2.13'
gem 'fitgem'

# Authentication/Authorization Support
gem 'devise'
gem 'omniauth-fitbit', :git => 'git://github.com/whazzmaster/omniauth-fitbit.git'

# Database
gem 'pg'

# Utility
gem 'visual-environments'
gem 'nifty-generators'

# Visualization
gem 'backbone-on-rails'
gem 'haml-rails'
gem 'simple_form'

# API Support
gem 'rabl'

# Monitoring
gem 'newrelic_rpm'

group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
  gem 'jquery-rails'
  gem 'handlebars_assets'
end

group :development, :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails'
  gem 'webrat'
  gem 'database_cleaner'
end

# Enable better error handling
group :development do
  gem 'meta_request', '~> 0.2.1', :require => 'meta_request'
  gem 'better_errors'
  gem 'binding_of_caller'
end

