# Multi-Auth System(Laravel 5.5)

## How to install:smiley:

```
cp .env.example .env
```

```
composer install
```

```
php artisan key:generate
```

```
php artisan migrate --seed
```

## Users:neckbeard:
	1. Employee
		* Login
		* Registration
		* Profile (Edit & Update)
	2. Company
		* Login
		* Registration
		* Profile (Edit & Update)
	3. Admin
		* Login
			email: admin@multiauth.dev
			pass : password
		* Approval
		* Reject
