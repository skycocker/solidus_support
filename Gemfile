source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

branch = ENV.fetch('SOLIDUS_BRANCH', 'master')
gem 'solidus_core_devise_token_auth', github: 'skycocker/solidus_devise_token_auth', branch: branch

# Specify your gem's dependencies in solidus_support.gemspec
gemspec

gem 'sprockets-rails'
gem 'sqlite3'
