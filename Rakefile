desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

namespace :db
  desc 'migrates the objects'
  task :migrate do
    require_relative
  end

  desc 'seeds the table'
  task :seed do
    require_relative
  end
end

desc 'starts the console'
task :console do
  Pry.start
end
