source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "bootstrap-sass", "3.3.7"
gem "brakeman", require: false
gem "carrierwave", "~> 1.0"
gem "cancancan", "~> 2.0"
gem "coffee-rails", "~> 4.2"
gem "daemons"
gem "delayed_job"
gem "delayed_job_active_record"
gem "devise"
gem "fabrication"
gem "ffaker"
gem "flipclockjs-rails", "~> 0.7.7"
gem "font-awesome-sass"
gem "jquery-rails"
gem "jbuilder", "~> 2.5"
gem "encrypt", "~> 0.1.0"
gem "mini_magick"
gem "mysql2", ">= 0.3.18", "< 0.5"
gem "omniauth"
gem "omniauth-facebook"
gem "omniauth-google"
gem "omniauth-github"
gem "omniauth-twitter"
gem "puma", "~> 3.0"
gem "rails", "~> 5.0.4"
gem "rails_best_practices"
gem "slim-rails", "~> 3.1"
gem "rubocop", ">= 0.35.0", require: false
gem "rubocop-checkstyle_formatter", require: false
gem "record_tag_helper", "~> 1.0"
gem "sass-rails", "~> 5.0"
gem "scss_lint", require: false
gem "scss_lint_reporter_checkstyle", require: false
gem "social-share-button", "0.2.1"
gem "turbolinks", "~> 5"
gem "timepiece"
gem "uglifier", ">= 1.3.0"
gem "will_paginate", "~> 3.1.0"
gem "will_paginate-bootstrap"

group :development, :test do
  # Call "byebug" anywhere in the code to stop execution and get a debugger console
  gem "rspec"
  gem "rspec-rails"
  gem "rspec-core"
  gem "rspec-expectations"
  gem "rspec-collection_matchers"
  gem "factory_girl_rails"
  gem "guard-rspec", require: false
  gem "byebug", platform: :mri
end

group :test do
  gem "shoulda-matchers"
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem "web-console", ">= 3.3.0"
  gem "listen", "~> 3.0.5"
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem "sidekiq"
