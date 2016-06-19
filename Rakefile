require "bundler"

Bundler.setup

task :default => %w(run)

task :run do

  # Make sure our project dir is on path
  $: << File.dirname(__FILE__)

  # Set our port
  ARGV << "--port=3000"

  # Run the main program
  require 'lib/main.rb'

end

