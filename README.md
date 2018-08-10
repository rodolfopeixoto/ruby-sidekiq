# Ruby Sidekiq

## COMMANDS

```
docker-compose run --rm sidekiq bundle exec sidekiq -r ./worker.rb
```

```
docker-compose run --rm sidekiq rackup config.ru -o 0.0.0.0 -p 3030 -q
```

```
docker-compose run --rm sidekiq bash
```

```
  bundle exec irb -r ./worker.rb
```
