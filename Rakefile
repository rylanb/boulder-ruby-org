# frozen_string_literal: true

begin
  require "git/cop/rake/setup"
rescue LoadError => error
  puts error.message
end

desc "Run code quality checks"
task code_quality: %i[git_cop]

task default: %i[code_quality]
