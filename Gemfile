source 'https://rubygems.org'

gem 'rails', git: 'https://github.com/rails/rails', branch: 'main'

ruby '3.1.0'

gem 'sassc-rails'

gem 'turbolinks'
gem 'terser'
gem 'jquery-rails'
gem 'jbuilder'
gem 'overcommit'
gem 'rails-html-sanitizer'
gem 'sdoc', group: :doc
gem 'sprockets-rails'

group :development do
  gem 'web-console'
end

group :development, :test do
  gem 'sqlite3'
  gem 'debug'
  gem 'spring'
  gem 'brakeman'
end

group :test do
  gem 'minitest-reporters'
  gem 'mini_backtrace'
  gem 'guard-minitest'
  gem 'guard'
end

group :production do
#HID:  gem 'pg' # HID on 10/3/2020
  gem 'rails_12factor'
end
