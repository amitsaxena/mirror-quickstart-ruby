source 'https://rubygems.org'

gem 'sinatra', require: 'sinatra/base'
gem 'haml'
gem 'google-api-client'
#gem 'sqlite3'
group :development, :test do
   gem 'sqlite3'
end

group :production, :staging do
   gem 'pg'
end
