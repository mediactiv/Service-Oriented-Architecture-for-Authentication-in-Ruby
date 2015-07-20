require "bundler/gem_tasks"

#@note @rails @ruby @rake creating a rake test task
require "rake/testtask"

Rake::TestTask.new do |t|
  t.pattern = "test/**/*_test.rb"
  t.libs << "test"
end
#@note @rails @ruby @rake set default rake task
task default: :test