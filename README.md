# Coding Challenge DevOp

## Context
The application was developed using Ruby on Rails.
The application requires a database for storing data.
The default database in Ruby on Rails is Sqlite3, but needs to be changed to PostgreSQL.
The application requires a nonpersistant Redis database.
The application is dependent on Sidekiq for background processing heavy tasks.

## Specification
- The main parts of the application are PostgreSQL, Redis, Rails application and Sidekiq.
- Each main part of the application is expected to run in a separate container.
- The entry point for the application is expected to run on port 80.
- Make sure everything is running with `docker-compose up`.

## Tasks
- [ ] Fork this repository
- [ ] Add your public ssh key to root
- [ ] Fullfill the specifications

## Extra Credit
These tasks are additional and won't mark you down. If you feel like it then give them a go :)
- Prepare some example to run this whole application in a Kubernetes environment.
- Use a configuration management tool (like Puppet, Chef or Ansible) to bootstrap the server.

