source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'
gem 'rails', '~> 6.0.0'

gem 'acts_as_list'
gem 'aws-sdk-s3', require: false
gem 'bootsnap', '>= 1.1.0', require: false
gem 'bootstrap'
gem 'coffee-rails', '~> 5.0'
gem 'image_processing'

gem 'jbuilder', github: 'rails/jbuilder', branch: 'master' # https://github.com/rails/rails/issues/35505

gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'mini_racer', platforms: :ruby
gem 'popper_js'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'tether-rails' 
gem 'turbolinks', '~> 5'
gem 'webpacker', '~> 4.0'


group :development, :test do
  gem 'dotenv-rails'
  gem 'factory_bot_rails'
  gem 'faker', :git => 'https://github.com/stympy/faker.git', :branch => 'master'
  gem 'pry'

  gem 'rspec-rails', git: 'https://github.com/rspec/rspec-rails', branch: '4-0-dev'
  # http://jessehouse.com/blog/2019/06/19/actionview-template-error-wrong-number-of-arguments-given-2/
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'capybara'
  gem 'launchy'
end
