# This file was generated by Appraisal

source "https://rubygems.org"

is_jruby = defined?(JRUBY_VERSION) || (defined?(RUBY_ENGINE) && 'jruby' == RUBY_ENGINE)

gem "sqlite3", :platform => [:ruby, :mswin, :mingw]
gem "jruby-openssl", :platform => :jruby
gem "activerecord-jdbcsqlite3-adapter", :platform => :jruby
gem "appraisal"
gem "rubysl", "~> 2.0", :platform => :rbx
gem "racc", :platform => :rbx
gem "minitest", :platform => :rbx
gem "rubinius-developer_tools", :platform => :rbx
gem "rails", "4.2.3"
gem 'rspec-rails', '~> 3.4'
gem 'rake'

gem 'oj', '~> 2.12.14' unless is_jruby
gem 'sidekiq', '>= 2.13.0' if RUBY_VERSION != '1.8.7'

if RUBY_VERSION.start_with?('1.9')
  gem 'sucker_punch', '~> 1.0'
elsif RUBY_VERSION.start_with?('2')
  gem 'sucker_punch', '~> 2.0'
end

gem 'sinatra'
gem 'resque'
gem 'delayed_job', :require => false
gem 'redis'
gem 'database_cleaner', '~> 1.0.0'
gem 'girl_friday', '>= 0.11.1'
gem 'generator_spec'

gemspec
