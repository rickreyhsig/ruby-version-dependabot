# frozen_string_literal: true

source 'https://rubygems.org'

source 'https://chime.jfrog.io/artifactory/api/gems/gems-local/' do
  gem 'chime-atlas'
  gem 'chime-hawker'
  gem 'chime-hawker_metadata'
  gem 'chime-schemas'
  gem 'chime-service-clients'
  gem 'lending_service_client'

  group :development, :test do
    gem 'rubocop-chime', '>= 3.1'
    gem 'rspec_junit_formatter', git: 'https://github.com/1debit/chime-rspec_junit_formatter'
  end
end

# Specify your gem's dependencies in chime-ring.gemspec
gemspec
