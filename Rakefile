$:.unshift File.dirname(__FILE__) + 'lib'

require 'rspec/core/rake_task'
RSpec::Core::RakeTask.new
task :default => :spec

desc "Expectativas de la clase Matriz"
task :spec do
        sh "rspec -I. spec/spec_matriz.rb"
end

