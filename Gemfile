source :rubygems

gem 'rails', '3.1.0.rc5'            # Only the latest, baby
gem 'heroku'                        # Deployment platform
gem 'devise'                        # User authentication
gem 'cancan'                        # User authorization
gem 'acts-as-taggable-on'           # Dead-simple tagging
gem 'kaminari'                      # Dead-simple pagination
gem 'rdiscount'                     # Markdown processor
gem 'high_voltage'                  # Easy static pages
gem 'paperclip'                     # Easy file attachments
gem 'sprockets', '>= 2.0.0.beta.12' # The asset pipline
gem 'sass-rails', "~> 3.1.0.rc"     # Like CSS, but better
gem 'compass', :git => 'git://github.com/chriseppstein/compass.git', :branch => 'rails31' # Hotsauce
gem 'coffee-script'                 # Like JavaScript, but better
gem 'coffee-filter'                 # Use CoffeeScript in HAML
gem 'jquery-rails'                  # You know what it is
gem 'uglifier'                      # Minifier for production
gem 'haml'                          # Slim and sexy templates
gem 'haml-rails'                    # Use HAML in generators
gem 'paper_trail'                   # For versioning, undo

group :development, :test, :cucumber do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'ruby-debug19'
end

group :test, :cucumber do
  gem 'factory_girl_rails'
  gem 'cucumber-rails'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'turn', :require => false
end

group :production do
  gem 'thin'
  gem 'pg'
end