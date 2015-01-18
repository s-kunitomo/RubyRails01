source 'https://rubygems.org'
ruby '2.1.5'

gem 'rails', '4.1.8'
gem 'bootstrap-sass', '2.3.2.0'
gem 'sprockets'
gem 'bcrypt-ruby'

#gem 'sqlite3'
group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
end

group :test do
  gem 'selenium-webdriver'
  gem 'capybara'
end

gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'

gem 'sdoc', '~> 0.4.0',          group: :doc

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin]

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end
