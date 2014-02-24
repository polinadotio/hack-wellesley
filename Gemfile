source 'https://rubygems.org'

ruby '1.9.3'
gem 'rails', '3.2.13'

#global gems 
gem 'jquery-rails'

##bootstrap and bootswatch
gem "bootstrap-sass", "~> 2.2.2.0" #gem "bootstrap-sass", ">= 2.1.1.0"
# twitter bootstrap css & javascript toolkit
gem 'twitter-bootswatch-rails', '~> 3.1.1'
# twitter bootstrap helpers gem, e.g., alerts etc...
gem 'twitter-bootswatch-rails-helpers'

gem "therubyracer", "~> 0.12.1"

gem "devise", ">= 2.1.2"
gem "cancan", ">= 1.6.8"
gem "rolify", ">= 3.2.0"
gem "simple_form", ">= 2.0.4"

#for adding static pages, yay!!!
gem 'high_voltage'

#for deploying to heroku 
gem 'heroku' 

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'sqlite3', :group => [:development, :test]
gem "rspec-rails", ">= 2.11.4", :group => [:development, :test]
gem "database_cleaner", ">= 0.9.1", :group => :test
gem "email_spec", ">= 1.4.0", :group => :test
gem "cucumber-rails", ">= 1.3.0", :group => :test, :require => false
gem "launchy", ">= 2.1.2", :group => :test
gem "capybara", ">= 2.0.1", :group => :test
gem "factory_girl_rails", ">= 4.1.0", :group => [:development, :test]
gem "quiet_assets", ">= 1.0.1", :group => :development
gem "figaro", ">= 0.5.0"
gem "better_errors", ">= 0.2.0", :group => :development
gem "binding_of_caller", ">= 0.6.8", :group => :development

group :production do
  gem 'pg' 
  #this won't install locally if I don't use 
  # bundle install --without production
  gem 'thin'
end


