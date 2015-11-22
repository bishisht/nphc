source 'https://rubygems.org'
# gem 'rails', '4.2.1'
gem 'rails', '4.2.2'
ruby '2.2.2'
gem 'mysql2'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
group :development, :test do
  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
end

group :spree do
    # gem 'spree', '3.0.1'
    # gem 'spree_core', '~> 3.0', '>= 3.0.4'
    gem 'spree'
    gem 'spree_core'
    gem 'spree_gateway', github: 'spree/spree_gateway', branch: '3-0-stable'
    gem 'spree_auth_devise', github: 'spree/spree_auth_devise', branch: '3-0-stable'
    gem 'spree_liqpay', github: 'kukareka/spree_liqpay'
    gem 'spree_paypal_express', github: 'spree-contrib/better_spree_paypal_express', branch: '3-0-stable'
    gem 'spree_static_content', github: 'spree-contrib/spree_static_content', branch: 'master'
    gem 'spree_editor'
end



group :production
    gem 'rails_12factor'
    gem 'pg'
    gem 'puma'
end

gem 'aws-sdk', '< 2.0'
gem 'paperclip'
gem 'newrelic_rpm'
