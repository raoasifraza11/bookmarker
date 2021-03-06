# BookMarker

BookMarker is simple app made in Laraval 5.2 framework using SQLite that can be used to bookmark important pages from the web to read them later. This is useful when you want to do research about some topic and organize page links according to category/folder. Another good option is that bookmarked pages can be annotated with highlights and comments. Pages can be bookmarked either manually via Admin interface or through provided Chrome browser extension.

## Why ?

Simple, because it was hard for me to manage my bookmarks in browser and I didn't want to use any online service either.

## Screenshot

![Dashboard](https://raw.githubusercontent.com/sarfraznawaz2005/bookmarker/master/snapshot.png)

## Installation

 - Clone or Download the repo
 - Run `composer install`
 - Create `database.sqlite` under `database` folder
 - Run `php artisan migrate`
 - Run `php artisan db:seed` to insert default admin user
 - Open the app in your browser

.

Default Admin Login Details: `admin@admin.com/admin123`

**Note:** You might witness CSS/Javascript files not loading if you try to access app like `http://localhost/bookmarker/public` so create a virtual host pointing to the app like `http://bookmarker.dev`.

## License

The BookMarker is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
