source 'https://rubygems.org'
ruby '2.0.0'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.0.0'

# for Heroku, replace "gem 'sqlite3'" in your Gemfile with this:
group :development, :test do
  # if you already have a 'group :development,:test' block in your
  # Gemfile, you can just move the line "gem 'sqlite3'" into it.
  gem 'sqlite3' # use SQLite only in development and testing
end
group :production do
  gem 'pg' # use PostgreSQL in production (Heroku)
end



gem 'sass-rails', '4.0.0'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.0'
gem 'jquery-rails', '2.2.1'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'
gem 'haml'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end
