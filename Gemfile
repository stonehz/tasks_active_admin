require 'rbconfig'
HOST_OS = Config::CONFIG['host_os']
source 'http://rubygems.org'
gem 'rails', '3.1.1'
gem 'sqlite3'
gem 'mysql'
gem 'activeadmin'
gem "meta_search",    '>= 1.1.0.pre'

group :assets do
  gem 'sass-rails',   '~> 3.1.4'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end
group :test do
  
  gem 'turn', :require => false
end
if HOST_OS =~ /linux/i
  gem 'therubyracer', '>= 0.8.2'
end
gem "devise", ">= 1.4.7"
gem "rails-footnotes", ">= 3.7", :group => :development
