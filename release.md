## Catatan rilis

Dibuat dengan `composer create-project laravel/laravel latihan-laravel --prefer-dist`
di [Kubuntu](http://kubuntu.org "") dengan Konsole.

Versi Laravel 5.1.4

Dibuat untuk kepentingan latihan *coding* PHP dengan framework [Laravel](http://laravel.com "").

### Commit 0

Mengawali rekaman *version control system*.

### Commit 1

Belajar **routing** dasar Laravel.

	php artisan make:controller Pendaratan --plain
	php artisan route:list

| Domain | Method        | URI  | Name | Action                                | Middleware |
|--------|---------------|------|------|---------------------------------------|------------|
|        | GET&#9134;HEAD | /    |      | Closure                               |            |
|        | GET&#9134;HEAD | home |      | App\Http\Controllers\Pendaratan@index |            |

### Commit 2

Melanjutkan tentang *routing*, dialihkan ke *view*.
Belajar Blade templating dan mengirim data ke *view*.

### Commit 3

Memindahkan function untuk routing `blog.index`.
