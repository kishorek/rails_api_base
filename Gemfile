source 'https://rubygems.org'
ruby '2.6.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.2'

gem 'activeadmin', '~> 1.4.3'
gem 'aws-sdk-s3', '~> 1', require: false
gem 'bootsnap', '~> 1.3.0'
gem 'delayed_job_active_record', '~> 4.1.3'
gem 'devise', '~> 4.4.3'
gem 'devise_token_auth', '~> 1.1.0'
gem 'draper', '~> 3.0.0'
gem 'figaro', '~> 1.1.1'
gem 'haml-rails', '~> 1.0.0'
gem 'jbuilder', '~> 2.7.0'
gem 'oj', '~> 3.7.12'
gem 'pg', '~> 0.18.2'
gem 'pry-rails', '~> 0.3.6'
gem 'puma', '~> 3.0'
gem 'rack-cors', '~> 0.4.0'
gem 'sendgrid', '~> 1.2.4'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  gem 'bullet', '~> 5.7.5'
  gem 'factory_bot_rails', '~> 4.8.2'
  gem 'pry-byebug', '~> 3.3.0', platform: :mri
  gem 'rspec-rails', '~> 3.8.0'
end

group :development do
  gem 'annotate', '~> 2.6.5'
  gem 'better_errors', '~> 2.1.1'
  gem 'binding_of_caller', '~> 0.7.2'
  gem 'brakeman', '~> 4.4.0'
  gem 'letter_opener', '~> 1.4.1'
  gem 'listen', '~> 3.0.5'
  gem 'rails_best_practices', '~> 1.19.4'
  gem 'reek', '~> 5.3.1'
  gem 'rubocop', '~> 0.65.0'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'faker', '~> 1.7.3'
  gem 'shoulda-matchers', '~> 3.1.1'
  gem 'simplecov', '~> 0.13.0', require: false
  gem 'webmock', '~> 2.3.2'
end

group :assets do
  gem 'uglifier', '~> 2.7.2'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i(mingw mswin x64_mingw jruby)
gem 'mysql2'