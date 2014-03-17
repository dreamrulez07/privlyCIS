#!/usr/bin/env rake
# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

Privly::Application.load_tasks


desc 'Run Jasmine Tests with Phantomjs'
task :phantomjs do
  sh %{phantomjs public/apps/vendor/phantom-jasmine/run_jasmine_test.coffee ./public/apps/Help/new.html}
end
