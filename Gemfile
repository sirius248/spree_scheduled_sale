source "https://rubygems.org"

# Declare your gem's dependencies in spree_scheduled_sale.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
# gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use debugger
# gem 'debugger'

gem 'sqlite3'
gem 'rails', '~> 4.0.5'
gem 'spree', '~> 2.2.0'

# gem 'spree', github: 'spree/spree', branch: '2-2-stable'

# gem 'paperclip', '~>3.0'


gem 'rspec-rails', :group => [:development, :test]

group :development, :test do
  gem 'ffaker'
end

group :test do
  gem 'flexmock'
  gem 'pg'
end