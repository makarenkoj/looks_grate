# Store

Build Ruby on Rails, gem spree

ruby '2.6.4'

gem 'rails', '~> 6.0.3'

[Install ImageMagick](https://imagemagick.org/script/download.php#unix)

`
bundle install
`

Note: if you run into Bundler could not find compatible versions for gem "sprockets": error message, please run

`
bundle update
`

Use the install generators to set up Spree

`
rails g spree:install --user_class=Spree::User
`

`
rails g spree:auth:install
`

`
rails g spree_gateway:install
`

`
bundle exec rails g spree_i18n:install
`

create admin:

`
rake spree_auth:admin:create
`
