source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.4'
# Use sqlite3 as the database for Active Record

gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails', '4.2.1'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

group :development, :test do
  gem 'sqlite3', '1.3.13'
  gem 'byebug', '9.0.0', platforms: [:mri, :mingw, :x64_mingw]
  #gem 'capybara', '~> 2.13'
  #gem 'selenium-webdriver'
end



group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring', '1.7.2'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
group :production do
  gem 'pg', '0.18.4'
end
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
