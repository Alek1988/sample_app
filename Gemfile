source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.1'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails', '>=2.13.1'
end

gem 'jquery-rails', '>=3.0.4'
gem 'uglifier'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'

gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'


group :development, :test do
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :doc do
  gem 'sdoc', '>=0.3.20', require: false
end
gem 'tzinfo-data'

  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'

gem 'coffee-script-source'

group :development do
  gem 'web-console', '>= 3.3.0'
end


