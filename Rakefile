ENV["SINATRA_ENV"] ||= "development"

require_relative './config/environment'
require 'sinatra/activerecord/rake'

desc "it opens an irb session with this library preloaded"
task :console do
  require 'irb'
  ARGV.clear
  IRB.start
end
