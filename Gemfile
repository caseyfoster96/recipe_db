source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.4'

gem 'puma', '~> 3.7'

gem 'sass-rails', '~> 5.0'

gem 'uglifier', '>= 1.3.0'

gem 'coffee-rails', '~> 4.2'

gem 'coffee-script-source', '1.9.0'

gem 'jquery-rails', '~> 4.3', '>= 4.3.1'

gem 'bootstrap-sass', '3.2.0.2'

gem 'nested_form_fields'

gem 'carrierwave', '~> 1.0'

gem 'turbolinks', '~> 5'

gem 'jbuilder', '~> 2.5'

gem 'fog-aws'


group :production do 
	gem 'pg'
	gem 'rails_12factor'
end

group :development, :test do
  gem 'sqlite3'
  
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
