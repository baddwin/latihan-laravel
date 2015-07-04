## Catatan rilis

Dibuat dengan `composer create-project laravel/laravel latihan-laravel --prefer-dist`
di [Kubuntu](http://kubuntu.org "") dengan Konsole.

Versi Laravel 5.1.4

Dibuat untuk kepentingan latihan *coding* PHP dengan framework [Laravel](http://laravel.com "").

### Commit 0

Mengawali rekaman *version control system*.

### Commit 1

Belajar **routing** dasar Laravel.

	php artisan make:controller Pendaratan
	php artisan route:list

| Domain | Method        | URI  | Name | Action                                | Middleware |
|--------|---------------|------|------|---------------------------------------|------------|
|        | GET&#124;HEAD | /    |      | Closure                               |            |
|        | GET&#124;HEAD | home |      | App\Http\Controllers\Pendaratan@index |            |
