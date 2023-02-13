# frozen_string_literal: true

source "https://rubygems.org"

gem "rake"

group :test do
  gem "benchmark-memory"
  gem "grpc", "1.52.0"
  gem "hiredis", "~> 0.6"
  gem "memory_profiler"
  gem "minitest"
  gem "mocha"
  gem "mysql2", "~> 0.5"
  gem "pry-byebug", require: false
  gem "rake-compiler"
  gem "hiredis-client", github: "redis-rb/redis-client"
  gem "redis", github: "redis/redis-rb"
  gem "timecop"
  gem "toxiproxy"
  gem "webrick"
  gem "activerecord", ">= 7.0.3"
end

group :lint do
  gem "rubocop-minitest", require: false
  gem "rubocop-rake", require: false
  gem "rubocop-shopify", require: false
  gem "rubocop", require: false
end

gemspec
