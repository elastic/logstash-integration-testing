require "bundler/gem_tasks"

require 'rspec'
require 'rspec/core/rake_task'

desc "Specs all at ones."
RSpec::Core::RakeTask.new(:spec) do |t|
  t.fail_on_error = true
  t.verbose = false
end
