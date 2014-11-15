source 'https://rubygems.org'

gem 'rails', '4.1.4'
gem 'bootstrap-sass'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
gem 'rails-html-sanitizer'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'bcrypt'

group :development, :test do
  gem 'sqlite3'
  gem 'byebug'
#  gem 'webconsole'  couldn't get this to work (JWD)
  gem 'spring'
end

group :test do
  gem 'minitest-reporters'
  gem 'mini_backtrace'
  gem 'guard-minitest'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end
