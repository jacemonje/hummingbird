source 'https://rubygems.org'
ruby '2.1.2'

gem 'rails', '~> 4.0'

gem 'annotate', require: false

gem 'grape'
gem 'active_model_serializers', '~> 0.8.0'

gem 'fastclick-rails', "~> 1.0"

gem 'pg', '0.17.1'

gem 'pghero'

gem 'hiredis'
gem 'redis', require: ['redis', 'redis/connection/hiredis']
gem 'redis-rails'

gem 'ember-rails', '~> 0.15'
gem 'ember-source', '1.8.0.beta.1'
gem 'ember-data-source', '1.0.0.beta.9'

gem 'react-rails', '~> 0.10.0.0'

gem 'rinku'
gem 'rack-cors', require: 'rack/cors'
gem 'sanitize', '~> 2.1'
gem 'oj'

gem 'fast_blank' # Faster `String#blank?`, which is used a lot by ActiveRecord.

# Was assets group.
gem 'sass-rails',   '~> 4.0'
gem 'zurb-foundation', '~> 4.3.0'
gem 'therubyracer', :platforms => :ruby
gem 'uglifier', '>= 1.0.3'
gem 'bootstrap-sass', '~> 3.2'
gem 'autoprefixer-rails', '~> 3.0'
gem 'non-stupid-digest-assets'
gem 'font-awesome-sass'

# Gems to help with development.
group :development do
  gem 'foreman'
  gem 'letter_opener'
  gem 'guard-livereload', require: false
  gem 'rack-livereload'
  gem 'rb-fsevent', require: false
  gem 'qunit-rails'
end

gem 'dotenv-rails', groups: [:development, :test]

gem 'rack-mini-profiler'
gem 'flamegraph'

# Testing
group :test do
  gem 'shoulda'
  gem 'timecop'
  gem 'mock_redis'
  gem 'mocha'
  gem 'fakeweb'
end

gem 'codeclimate-test-reporter', group: :test, require: nil

gem 'haml', '~> 4.0'
gem 'haml-rails'
gem 'simple_form'
gem 'rdiscount'

# Attachments
gem "paperclip", "~> 4.1"
gem 'paperclip-optimizer'
gem 'delayed_paperclip', "~> 2.8"
gem 'aws-sdk', '~> 1.45'

# Better URLs.
gem 'friendly_id', github: 'joshfabian/friendly_id'

# Authentication.
gem 'devise', '~> 3.2'
gem 'devise-async' # Async email for Devise
gem 'omniauth'
gem 'omniauth-facebook', '~> 2.0'

# Authorization.
gem 'cancan', "~> 1.6"

# For pagination.
gem 'kaminari', '~> 0.16'

# Background jobs
gem 'sidekiq', '~> 3.1'

gem 'sinatra', :require => nil

gem 'pg_search', '~> 0.7'

# Admin panel
gem "rails_admin"

# Use Unicorn as the app server
gem 'unicorn', "~> 4.8"

# Needed for Dropbox backup
gem 'dropbox-api'

# Needed for MAL import.
gem 'nokogiri', require: false

# Needed for Hulu import
gem 'hooloo', require: false
gem 'rubyfish' # String matching

# Image optimization
gem 'image_optim', '~> 0.13', require: false

# Metrics
gem 'mixpanel'

# SEO
gem 'sitemap_generator'

gem 'twitter-typeahead-rails'
