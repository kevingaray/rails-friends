source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 6.1.5.1'
# sending to development
# gem 'sqlite3', '~> 1.3', '>= 1.3.11'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'sqlite3', '~> 1.3', '>= 1.3.11'
end

# added production 
group :production do
  gem 'pg', '~> 1.3', '>= 1.3.5'
  # gem 'rails_12factor', '0.0.2'
end 

# added
gem "tzinfo-data"
gem 'webpacker', '~> 3.5'
gem 'psych', '< 4'
gem 'rspec-rails'
gem 'factory_girl_rails'
# added
gem 'devise', '~> 4.8', '>= 4.8.1'
