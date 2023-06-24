Using `rails_performance` gem to see the performance of our application

### Following commands were run to create this application

```bash
rails new using_rails_performance
```

```bash
bundle add rails_performance faker
```

```bash
rails g rails_performance:install
```

```bash
rails g scaffold Article title body:text
```

```bash
rails db:migrate && rails db:seed
```

Configure the `config/initializers/rails_performance.rb` file for credentials
