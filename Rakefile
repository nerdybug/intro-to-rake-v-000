namespace :db do
  task :environment do
    require_relative './config/environment'
  end

  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end

  desc 'seed the database with dummy data'
  task :seed do
    require_relative './db/seeds.rb'
  end
end
