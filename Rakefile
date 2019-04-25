# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require_relative 'config/application'

Rails.application.load_tasks

task :server do
  exec 'bundle exec rails s -p 3001'
end

task :client do
  exec 'cd client && npm start'
end

task :start do
  exec 'foreman start -p 3000'
end