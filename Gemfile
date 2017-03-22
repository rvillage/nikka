source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Application Server
gem 'puma'

# Assets
gem 'jbuilder'
gem 'uglifier'

# Database
gem 'pg'

# Framework
gem 'dotenv-rails'
gem 'rails', '~> 5.0.2'

# JavaScript
gem 'coffee-rails'
gem 'jquery-rails'

# Package Manager
gem 'bundler'

# View
gem 'haml-rails'
gem 'sass-rails'

group :development, :test do
  # Debug
  gem 'awesome_print'
  gem 'pry-byebug'
  gem 'pry-rails'

  # Framework
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :test do
  # TDD
  gem 'rspec-rails'
end
