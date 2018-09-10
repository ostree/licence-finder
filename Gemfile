source 'https://rubygems.org'

gem 'rails', '5.2.1'
gem 'rails-controller-testing'
gem 'govuk_app_config', '~> 1.8.0'
gem 'plek', '2.1.1'

gem "mongoid", '~> 6.2.0'
gem 'elasticsearch'

gem 'mongoid_rails_migrations', '~> 1.1.0'

if ENV['API_DEV']
  gem 'gds-api-adapters', :path => '../gds-api-adapters'
else
  gem 'gds-api-adapters', '~> 53.0'
end

if ENV['SLIMMER_DEV']
  gem "slimmer", :path => '../slimmer'
else
  gem "slimmer", '13.0.0'
end

gem 'sass-rails', '~> 5.0.7'
gem 'uglifier', '~> 4.1.18'

gem 'govuk_frontend_toolkit', '~> 7.6.0'
gem 'govuk_publishing_components', '~> 9.16.1'

gem 'govuk-lint', '~> 3.8.0'

group :development, :test do
  gem 'capybara', '~> 3.7.1'
  gem 'database_cleaner', '~> 1.7.0'
  gem 'factory_bot_rails'
  gem 'govuk-content-schema-test-helpers'
  gem 'govuk_test'
  gem 'pry-rails'
  gem 'rspec-rails', '~> 3.8.0'
  gem 'webmock', '~> 3.4.2'
end
