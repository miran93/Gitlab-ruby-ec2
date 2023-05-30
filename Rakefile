namespace :assets do
  task precompile: :environment do
  require 'rake/testtask'
task default: "test"
Rake::TestTask.new do |task|
  task.pattern = 'test/*_test.rb'
  end
end
