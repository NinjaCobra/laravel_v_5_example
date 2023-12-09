### Features ###

* Home page
* Custom error pages 403, 404 and 503
* Authentication (registration, login, logout, password reset, mail confirmation, throttle)
* Users roles : administrator (all access), redactor (create and edit post, upload and use medias in personnal directory), and user (create comment in blog)
* Blog with nested comments
* Search in posts
* Tags on posts
* Contact us page
* Admin dashboard with users, posts, articles, medias, settings, notifications and comments
* Multi users medias gestion
* Localization (English, French and Chinese)
* Application tests
* Thumbs creation for images
* Notifications to send emails and notify redactors for new comments

### Tests ###

When you want to launch the tests refresh and populate the database :

`php artisan migrate:fresh --seed`

You must have default settings and **en** language. You must also add provider in **config/app.php**.
