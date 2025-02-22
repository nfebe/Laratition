# Laratition

Open source contest or tournament managment platform, built in Laravel. The name Laratition comes from hold up; 

```php
echo substr("Laravel", 0, 4).substr("competition", 5);
```

## Features

- Authentication
- Competitions - Add and manage competitions [CRUD]
- Submissions - Registered users can submit solutions to competitions
- Leaderboard - Top users can be tracked on leaderboard
- Votes - Submissions and competitions can be voted


## Setup instructions

### Prerequisites

- Docker
- Docker Compose

### Quick installation guide
- `git clone git@github.com:nfebe/Laratition.git`
- `cd Laratition`
- `cp .env.example .env`
- `docker compose up -d app`
- `docker compose exec app composer install`
- `docker compose exec app php artisan key:generate`
- `docker compose exec app php artisan migrate`
- `docker compose exec app php artisan db:seed`

## Screenshots

## Contributing 

## License

Laratition is licensed under [MIT license](https://opensource.org/licenses/MIT).
