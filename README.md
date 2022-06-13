# Tutorial-Laravel9-Voyager

---

## Laravel 本体他のインストール

- [YA-androidapp/Laravel9-sail-example-app](https://github.com/YA-androidapp/Laravel9-sail-example-app#readme)

```bash
curl -s "https://laravel.build/laravel9-voyager" | bash
cd laravel9-voyager && ./vendor/bin/sail up -d
nano docker-compose.yml

./vendor/bin/sail up -d

./vendor/bin/sail composer require laravel/breeze --dev
./vendor/bin/sail php artisan breeze:install
./vendor/bin/sail npm install
./vendor/bin/sail npm run dev
./vendor/bin/sail php artisan migrate
```

- [http://localhost/register](http://localhost/register)
- [http://localhost/login](http://localhost/login)

```bash
./vendor/bin/sail composer require laravel-lang/publisher laravel-lang/lang --dev
./vendor/bin/sail php artisan lang:add ja
```

---

Copyright (c) 2022 YA-androidapp(<https://github.com/YA-androidapp>) All rights reserved.
