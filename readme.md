# Simple Blog built on Laravel PHP Framework.

The blog features are :
+ twitter bootstrap layout implemented by bootstrapper bundle
+ user log in and authentification 
+ display all posts in paginated view
+ create new posts
+ delete posts

Copy this folder or create a symbolic link to your server's htdocs or www folder.

Create a database "blog" and make sure your database settings in config -> database.php match your database setup.

Then run migrations in the terminal or command line to set up tables from migrations: 
<pre>
php artisan migrate:install
php artisan migrate
</pre>
If everything is alright, you should see that migration tables are created successfully.

Then in your browser navigate to where your folder is on your server, and in the "public" of that folder (in my case it is localhost/blog/public). You should see an empty blog.
Click Login on the top right, and then login with the following username and password:
<pre>
admin
password
</pre>

That's it, you should be able to post and delete entries now!

## Contributing to This code

Contributions are encouraged and welcome. Submit pull requests or ask questions if something's not clear
