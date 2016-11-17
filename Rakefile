require 'zlib'
require 'sinatra/activerecord'
require 'sinatra/activerecord/rake'

ActiveRecord::Base.establish_connection(
      :adapter => ENV['DB_ADAPTER'],
      :database => ENV['DB_NAME']
      :host     => ENV['DB_HOST'],
      :username => ENV['DB_USER'],
      :password => ENV['DB_PW']
)