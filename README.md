# Blueprint Laravel microservice project

### App containers [Laravel, MySQL, Nginx]
### Utility containers [Composer, Artisan]

---

### Create laravel project
```
docker-compose run --rm composer create-project --prefer-dist laravel/laravel .
```

### Start project
```
docker-compose up -d --build server
```

### Example artisan command
```
docker-compose run --rm artisan migrate
```