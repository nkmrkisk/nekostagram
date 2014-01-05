source 'https://rubygems.org'

ruby '2.1.0'

gem 'rails', '4.0.2'

gem 'thin', '1.6.1'
gem 'pg', '0.17.1'
gem 'haml', '4.0.4'
gem 'haml-rails', '0.5.3'
gem 'sass', git: 'git://github.com/nex3/sass.git',
            branch: 'master'
gem 'sass-rails', '4.0.1'
gem 'compass', '1.0.0.alpha.17'
gem 'compass-rails', '1.1.2'
gem 'bootstrap-sass', '2.3.2.2'
gem 'jquery-rails', '3.0.4'
gem 'handlebars_assets', '0.15'
gem 'instagram', '0.10.0'
gem 'jbuilder', '2.0.1'
gem 'ejs', '1.1.1'
gem 'browser', '0.3.2'
gem 'coffee-rails', '4.0.1'
gem 'uglifier', '2.4.0'

group :production, :staging do
  gem 'rails_12factor', '0.0.2' # for Heroku assets precompile
end

group :development do
  gem 'better_errors', '1.0.1'
  gem 'binding_of_caller', '0.7.2'
  gem 'brakeman', '2.3.1'
  gem 'pry-rails', '0.3.2'
  gem 'pry-remote', '0.1.7'
  gem 'xray-rails', '0.1.12'
  gem 'figaro', '0.7.0'
end

group :development, :test do
  gem 'rspec-rails', '2.14.1'
end
