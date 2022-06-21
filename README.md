# awesome-ruby-on-rails
## Authentication
devise is the most popular. OmniAuth is popular for SNS login.

* devise
* authlogic
* sorcery

## test
rspec is the first choice for me. The syntax is rich.

* rspec
* minitest

For seed data, facotry_bot is popular.

## admin
I recommend not using gem if you want customization.

* (rails_admin)

## model
* annotate: table difinition in model file
* (activerecord-import): bunlk import. native insert_all is another choice.
* (enumerize): enum. native enum is another choice.
* discard: soft delete

## file upload
* carrierwave: good form helper is available
* active_storage: Rails official

## Form
You don't need gem. Simply use

* PORO: Plain Old Ruby Object
* Active Model

## Decorator
* draper
* active_decorator

## json serialization
* jbuilder

## pagination
* kaminari
* will_paginate

## view
* haml
* slim

For view component, gem is available, but I often use just partial.
* (cells)
* (view_component)

## lint
* rubocop: lint ruby
* haml-lint: lint haml
* overcommit: run lint by git hook

## error check
* bullet: N+1 check
* (brakeman): vulnerability check. Github vunlenrability check is the similar service.

## job queue
* Sidekiq
* Delayed::Job
* (Resque)

## scheduler
* whenever

## deploy
* capistrano

## full text search
* elasticsearch-rails

## session
* redis-actionpack
* (kredis)

## web server
* unicorn
* puma
