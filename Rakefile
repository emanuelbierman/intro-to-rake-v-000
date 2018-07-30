desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

namespace :db do
  desc 'migrate changes to your database'
  task :migrate => :environment do
    Student.create_table
  end

  desc 'seeds the table'
  task :seed do
    require_relative './db/seeds.rb'
  end
end

desc 'starts the console'
task :console do
  Pry.start
end
