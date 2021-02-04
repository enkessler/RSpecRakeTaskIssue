require 'rspec/core/rake_task'


desc 'Run all of the RSpec tests'
task :run_rspec_tests
RSpec::Core::RakeTask.new(:run_rspec_tests, :command_options) do |t, args|
  t.rspec_opts = args[:command_options] if args[:command_options]
end
