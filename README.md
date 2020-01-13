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
- [ ] Send the solution as `git format-patch`

## Extra Credit
These tasks are additional and won't mark you down. If you feel like it then give any of them a go.
- Add an additional container to the Docker setup which acts as an SFTP server which is accessible from the within the Ruby on Rails application and the outside world.
- Prepare some example to run this whole application in a Kubernetes environment.
- Use Ansible management tool to bootstrap the server.

## Why doesn't the task include ... ?
Feel free to contact us with your ideas :yellow_heart:
