namespace :db do
    desc 'Creates a new student table'
    task :environment do
        require_relative './config/environment'
    end

    desc 'Creates a new student table'
    task :migrate => :environment do
        Student.create_table
    end

    desc 'Seeds a database'
    task :seed do
        require_relative './db/seeds.rb'
    end
end

namespace :greeting do

    task :hello do
        puts 'hello from Rake!'
    end

    task :hola do
        puts 'hola de Rake!'
    end
end
