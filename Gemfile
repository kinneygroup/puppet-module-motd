source "https://rubygems.org"

puppetversion = ENV.key?('PUPPET_VERSION') ? "= #{ENV['PUPPET_VERSION']}" : ['>= 3.3']
gem 'puppet', puppetversion
gem 'puppetlabs_spec_helper', '>= 0.1.0'
gem 'puppet-lint', '>= 0.3.2'
gem 'facter', '>= 1.7.0', "< 1.8.0"
gem 'rspec-puppet', :git => 'https://github.com/rodjek/rspec-puppet.git'
gem 'simplecov', :platforms => [:ruby_19, :ruby_20]
gem 'coveralls', :platforms => [:ruby_19, :ruby_20]
