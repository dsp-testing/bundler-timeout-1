# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby File.read('.ruby-version').strip

source 'https://gems.railslts.com' do
  gem 'rails', '4.2.11.38'

  gem 'actionmailer',     require: false
  gem 'actionpack',       require: false
  gem 'actionview',       require: false
  gem 'activejob',        require: false
  gem 'activemodel',      require: false
  gem 'activerecord',     require: false
  gem 'activesupport',    require: false
  gem 'rack',             require: false
  gem 'railslts-version', require: false
  gem 'railties',         require: false
end

source 'https://enterprise.contribsys.com' do
  gem 'sidekiq-ent'
  gem 'sidekiq-pro'
end

gem 'globalize',                  '5.3.1'
gem 'mysql2',                     '0.5.5'

gem 'activerecord-import',                '2.0.0'
gem 'activerecord-nulldb-adapter',        '0.4.0', require: ENV['DATABASE_URL'].to_s.match?(%r{\Anulldb://})
gem 'analytics-ruby',                     '2.4.0', require: 'segment/analytics' # Segment analytics SDK
gem 'apollo-federation'
gem 'asset_sync',                         '2.19.1'
gem 'aws-sdk',                            '2.11.632'
gem 'aws-sdk-v1',                         '1.67.0'
gem 'bootsnap',                           '1.18.4', require: false
gem 'carmen',                             github: 'madetech/carmen', ref: '344dfa6'
gem 'cloud-integration-layer-ruby-client', '1.9.13', github: 'onrunning/cloud-integration-layer-ruby-client', require: false
gem 'crawler_detect',                     '1.2.1'
gem 'createsend',                         '4.1.2'
gem 'createsend-rails',                   tag: 'v1.1.3', github: 'onrunning/createsend-rails', require: 'create_send_rails'
gem 'csv',                                '3.3.0'
gem 'databasedotcom',                     '1.3.5'
gem 'delayed_cron_job',                   '0.9.0'
gem 'delayed_job',                        '4.1.9'
gem 'delayed_job_active_record',          '4.1.6'
gem 'dotenv-rails',                       '2.8.1'
gem 'dry-struct',                         '1.6.0'
gem 'flipper',                            '0.17.2'
gem 'flipper-active_record',              '0.17.2'
gem 'flipper-active_support_cache_store', '0.17.2'
gem 'flipper-ui',                         '0.17.2'
gem 'fog-aws',                            '3.30.0' # used by asset_sync
gem 'has_secure_token',                   '1.0.0' # backport of Rails 5/6 feature
gem 'hiredis',                            '0.6.3'
gem 'htmlcompressor',                     '0.4.0'
gem 'httparty',                           '0.22.0'
gem 'json',                               github: 'onrunning/json', branch: 'v1.8.6-with-ruby3-compat'
gem 'jsonrpc-client',                     '0.1.3'
gem 'jwt',                                '2.10.1'
gem 'mime-types',                         github: 'onrunning/ruby-mime-types', branch: 'v2.99.3-with-ruby3-compat'
gem 'net-sftp',                           '4.0.0'
gem 'newrelic_rpm',                       '9.16.1'
gem 'psych',                              '< 4' # https://stackoverflow.com/a/71192990/211060
gem 'rack-attack',                        '6.7.0'
gem 'rack-rewrite',                       '1.5.1'
gem 'readthis',                           '2.2.0'
gem 'responders',                         '2.4.1'
gem 'ruby3-backward-compatibility',       '1.4.0'
gem 'sekrets',                            github: 'onrunning/sekrets', ref: '451963e'
gem 'shopify_api',                        '14.1.0'
gem 'sidekiq',                            '~> 5.0'
gem 'sprockets',                          '3.7.2'
gem 'webpacker',                          '4.3.0'

gem 'avatax',                     '22.10.0', require: false
gem 'cpf_cnpj',                   '0.5.0'
gem 'deface',                     github: 'onrunning/deface', branch: 'v10-with-relaxed-nokogiri'
gem 'solidus',                    '1.1.4'
gem 'solidus_auth_devise',        '1.6.4'
gem 'solidus_avatax_certified',   '1.0.0'
gem 'solidus_globalize',          github: 'solidusio-contrib/solidus_globalize', branch: 'master', ref: '994a8e69'
gem 'solidus_i18n',               '1.3.0'
gem 'solidus_multi_domain',       '1.5.0'

gem 'adyen-ruby-api-library',     '9.0.0'
gem 'algoliasearch-rails',        '1.26.0'
gem 'contentful',                 '1.2.2'
gem 'coverband',                  '6.1.4'
gem 'google-apis-drive_v3',       '0.46.0'
gem 'googleauth',                 '1.9.1'
gem 'graphql',                    '1.13.23'
gem 'graphql-batch',              '0.6.0'
gem 'graphql-preload',            github: 'onrunning/graphql-preload'
gem 'graphql-result_cache',       github: 'onrunning/graphql-result_cache'
gem 'image_optim_pack',           '0.11.1.20241130'
gem 'jbuilder',                   '2.9.1'
gem 'lograge',                    '0.14.0'
gem 'paperclip-optimizer',        '2.0.0'
gem 'paper_trail',                '10.3.1'
gem 'pry'
gem 'puma',                       '6.5.0'
gem 'puma-newrelic',              '0.1.6'
gem 'remote_syslog_logger',       '1.0.4'
gem 'rich_text_renderer',         '0.3.0'
gem 'rollbar',                    '3.4.2'
gem 'ruby-prof', require: false
gem 'sailthru-client',            '4.3.0'
gem 'sanitize',                   '6.1.3'
gem 'stackprof',                  '0.2.17', require: false
gem 'strong_migrations',          '0.3.1'
gem 'uglifier',                   '4.2.0'
gem 'with_advisory_lock',         '4.6.0'

group :development do
  gem 'active_record_query_trace',        '1.8'
  gem 'bullet',                           '8.0.0'
  gem 'flamegraph',                       '0.9.5', require: false
  gem 'graphiql-rails',                   '1.10.0'
  gem 'guard-rspec',                      '4.7.3', require: false
  gem 'memory_profiler',                  '1.0.2', require: false
  gem 'meta_request',                     '0.7.2'
  gem 'quiet_assets',                     '1.1.0'
  gem 'rack-mini-profiler',               '3.3.0', require: false
end

group :development, :test do
  gem 'graphql-schema_comparator', '1.2.0'
  gem 'knapsack_pro',              '7.13.1'
  gem 'pry-byebug',                '3.10.1'
  gem 'pry-rails',                 '0.3.9'
  gem 'rb-readline',               '0.5.5'
  gem 'rubocop',                   require: false
  gem 'rubocop-graphql',           require: false
  gem 'rubocop-rails',             require: false
  gem 'scss_lint',                 '0.60.0', require: false
  gem 'spring',                    '2.1.1', require: false
  gem 'spring-commands-rspec',     '1.0.4'
end

group :development, :staging, :preview do
  gem 'phraseapp-in-context-editor-ruby', '1.4.0', require: false
end

group :development, :staging, :preview, :test do
  gem 'makara', '~> 0.5.0'
  gem 'request_store', '1.7.0', require: true
end

group :test do
  gem 'brakeman' # Always latest
  gem 'capybara',                 '3.40.0'
  gem 'database_cleaner',         '1.99.0'
  gem 'db-query-matchers',        '0.14.0'
  gem 'factory_girl',             '4.9.0'
  gem 'ffaker',                   '1.32.1'
  gem 'rspec',                    '3.13.0'
  gem 'rspec-activemodel-mocks',  '1.2.0'
  gem 'rspec-its',                '2.0.0'
  gem 'rspec-rails',              '4.1.2'
  gem 'rspec-retry',              '0.6.2'
  gem 'shoulda-matchers',         '4.5.1'
  gem 'simplecov',                '0.22.0', require: false
  gem 'super_diff',               '0.15.0'
  gem 'test-prof',                '1.3.3'
  gem 'vcr',                      '6.3.1'
  gem 'webdrivers',               '5.3.1'
  gem 'webmock',                  '3.24.0'
end
