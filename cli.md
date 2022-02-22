### List of all the commands executed

* create the project
```bash
rails new foodlog
```

* if the port `3000` is already in use, start the server using the `p` flag on another port
```bash
rails server -p 3001
```

* add a [scaffold](https://www.rubyguides.com/2020/03/rails-scaffolding)
```bash
rails generate scaffold Entry meal_type:string calories:integer proteins:integer carbohydrates:integer fats:integer
```

* fix a pending migration error (the fix was suggested on the web interface)
```bash
bin/rails db:migrate RAILS_ENV=development
```

* to see all the routes go to `http://localhost:3001/rails/info/routes` or from the cli
```bash
rails routes
```

