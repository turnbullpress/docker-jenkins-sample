require 'rubygems'
require 'rspec/core/rake_task'
require 'ci/reporter/rake/rspec'

desc "Run those specs"
task :spec => [ "ci:setup:rspec" ]
RSpec::Core::RakeTask.new(:spec) do |t|
  t.rspec_opts = %w{--colour --format progress}
  t.pattern = 'spec/*_spec.rb'
end
