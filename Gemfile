source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'
gem 'rails', '~> 5.0.3'
gem 'sass-rails', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'uglifier', '>= 1.3.0'

group :development, :test do
  gem 'capybara', '~> 2.12'
  gem 'database_cleaner', '~> 1.5', '>= 1.5.3'
  gem 'factory_girl_rails', '~> 4.8'
  gem 'faker', '~> 1.7', '>= 1.7.2'
  gem 'guard', '~> 2.14', '>= 2.14.1'
  gem 'guard-livereload', '~> 2.5', '>= 2.5.2'
  gem 'guard-rspec', '~> 4.7', '>= 4.7.3'
  gem 'pry'
  gem 'rspec-rails', '~> 3.5', '>= 3.5.2'
  gem 'shoulda-matchers', '~> 3.1', '>= 3.1.1'
  gem 'spring-commands-rspec'
end

group :development do
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
