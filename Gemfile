# frozen_string_literal: true

source 'https://rubygems.org'

gemspec

gem 'ruby-kafka', git: 'https://github.com/fist28/ruby-kafka.git', branch: 'scram-thread-save'

group :development, :test do
  gem 'benchmark-ips'
end

group :test do
  gem 'rspec'
  gem 'simplecov'
  gem 'timecop'
end
