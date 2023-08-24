source "https://rubygems.org"

ruby "2.7.1"

gem "active_link_to"
gem "active_model_serializers", "0.10.12"
gem "administrate", "0.17.0"
gem "analytics-ruby", "~> 2.2.2", require: "segment/analytics"
gem "attr_extras"
gem "autoprefixer-rails"
gem "bourbon", "~> 5.0"
gem "email_validator", ">= 2.1.0"
gem "faraday", "~> 1.0"
gem "haml-rails", "~> 2.1", ">= 2.1.0"
gem "high_voltage"
gem "inifile"
gem "inline_svg", ">= 1.7.2"
gem "jquery-rails", ">= 4.5.0"
gem "jwt"
gem "neat", "~> 1.9"
gem "nokogiri", ">= 1.8.2"
gem "octokit"
gem "omniauth-github"
gem "omniauth-rails_csrf_protection", ">= 1.0.0"
gem "paranoia", "~> 2.4.3"
gem "pathspec"
gem "pg"
gem "puma"
gem "rails", "~> 6.1.7", ">= 6.1.7.5"
gem "sentry-raven"
gem "sidekiq"
gem "sinatra", "~> 2.0"
gem "stripe"
gem "uglifier", ">= 2.7.2"
gem "webpacker", ">= 4.3.0"
gem "webpacker-react", "~> 1.0.0.beta.1"

group :staging, :production do
  gem "rack-timeout"
  gem "rails_12factor"
end

group :development, :test do
  gem "bundler-audit", require: false
  gem "byebug"
  gem "dotenv-rails", ">= 2.7.6"
  gem "foreman"
  gem "listen"
  gem "rspec-rails", ">= 4.0.0"
end

group :test do
  gem "capybara"
  gem "factory_bot_rails", ">= 5.2.0"
  gem "launchy"
  gem "selenium-webdriver", ">= 4.0.0.alpha4"
  gem "shoulda-matchers", ">= 4.3.0"
  gem "webmock"
end
