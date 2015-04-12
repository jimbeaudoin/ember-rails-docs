
# Executed Commands
[<= Back](https://github.com/jimbeaudoin/ember-rails-tdd-docs)

Generate a new rails project. `-B` for skip-bundle & `-S` for skip-sprockets
```sh
rails new backend -B -S
```

Generate a new ember-cli project.
```sh
ember new frontend --skip-git
```

Remove Backend Assets Folder
```sh
rm -rf backend/app/assets
```

Unclassified Commands
```sh
npm install --save-dev ember-cli-pretender
ember install ember-cli-pretender
ember g adapter application
rails g model student name:string
rake db:migrate
rake db:seed
rails g serializer student
```