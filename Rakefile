require 'rake/testtask'

Rake::TestTask.new("test") do |test|
  test.libs << 'test'
  test.pattern = 'test/unit/**/*_test.rb'
  test.verbose = true
end

task :default => :test
