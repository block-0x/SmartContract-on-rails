source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'
gem 'rails', '5.2.6'

gem 'pg', '~> 0.18'
gem 'puma', '~> 5.0'

gem 'active_model_serializers'
gem 'airbrake', '~> 6.2.1'
gem 'rack-cors'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

  gem 'capistrano', '~> 2.15'
  gem 'rvm-capistrano', require: false
end

group :production do
  gem 'unicorn'
end

gem 'eth'
gem 'ethereum.rb', github: 'rubyruby/ethereum.rb'
