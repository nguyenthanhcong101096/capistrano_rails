require 'capistrano/setup'
require 'capistrano/deploy'

require 'capistrano/rbenv'
require 'capistrano/bundler'
# require 'capistrano/rails/assets'
require 'capistrano/rails/migrations'
require 'capistrano/puma'
require 'capistrano/sidekiq'
require 'seed-fu/capistrano3'

Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }