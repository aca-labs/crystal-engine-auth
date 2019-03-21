source 'https://rubygems.org'

gem 'rails', '~> 5.0', '>= 5.0.0.1'

# High performance web server
gem 'agoo'

# Database
gem 'nobrainer'

# Authentication
#gem 'doorkeeper'
#gem 'doorkeeper-jwt'
#gem 'doorkeeper-rethinkdb'
#gem 'coauth', github: 'QuayPay/coauth', branch: 'couchbase-orm'

# Logging
gem 'mono_logger'
gem 'lograge'

# Fast JSON parsing
gem 'yajl-ruby'

# Runtime debugging
gem 'rbtrace'


group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug',      platform: :mri
  gem 'web-console', platform: :mri
end

group :development do
  gem 'listen', '~> 3.0.5'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  #gem 'spring'
  #gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data'  #, platforms: [:mingw, :mswin, :x64_mingw, :jruby]
