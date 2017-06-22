source 'https://rubygems.org'

# defaults
gem 'rails', '4.2.6'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc

# added
gem 'simple_form'
gem 'bootstrap-sass', '~> 3.2.0'
gem 'figaro'


group :development do
  gem 'web-console', '~> 2.0'
  gem 'spring'
end
group :development, :test do
  gem 'sqlite3'

  gem 'byebug'
  gem 'pry-rails'           # Causes rails console to open pry
  gem 'pry-byebug'          # Adds step, next, finish, and continue commands and breakpoints
  gem 'pry-stack_explorer'  # Navigate the call-stack
  gem 'annotate'            # Annotate all your models, tests, fixtures, and factories
  gem 'quiet_assets'        # Turns off the Rails asset pipeline log
  gem 'better_errors'       # Replaces the standard Rails error page with a much better and more useful error page
  gem 'binding_of_caller'   # Advanced features for better_errors advanced features (REPL, local/instance variable inspection, pretty stack frame names)
  gem 'meta_request'        # Supporting gem for Rails Panel (Google Chrome extension for Rails development).
end
group :production do
  gem 'rails_12factor'
  gem 'pg'
end