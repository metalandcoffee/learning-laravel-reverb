# My Progress Through Laracast Series
## Get Real With Laravel Reverb
https://laracasts.com/series/get-real-with-laravel-reverb

I am working through this tutorial and had to do some pre-setup to get the source code from the series up and running locally.
https://laravel.com/docs/12.x/installation#creating-an-application

I created a fresh Laravel app and am running it on a PHP development server using `php artisan serve`.

I then copied over the files from the "Get Real with Laravel Reverb" using this command.
`rsync -a --remove-source-files --progress get-real-with-laravel-reverb/ learning-laravel-reverb`

After running that command, I noticed that the following files were missing.
- database.sqlite
- .env
I probably could modify the above command to not clear those files but I didn't feel like looking into it.

I restored those files. Then ran a database migration and database seed to get the app from the course up and running.

It takes you to the login route by default but I manually switched to the register route so I could create a new user. Then it took me to the Slack-look-alike UI.