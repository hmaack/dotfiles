require 'rubygems'
require 'peridot'
require 'dotenv/tasks'

# $ rake dotfiles
namespace :dotfiles do
  # $ rake dotfiles:sublime
  desc 'Link Sublime configuration folder'
  task :sublime do
    sublime_configuration_files.map do |f|
      link_file(repo_file(f), sublime_configuration_file(f))
    end
  end
end

def sublime_configuration_file(file)
  file_name = File.basename(file)
  "#{Dir.home}/Library/Application Support/Sublime Text 3/Packages/User/#{file_name}"
end

def sublime_configuration_files
  Dir['sublime3/*']
end
