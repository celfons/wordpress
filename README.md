<pre>
https://signup.heroku.com/ <-Create your account
sudo apt install git
sudo snap install --classic heroku
heroku login
git clone https://github.com/php4dev/heroku-wordpress.git
cd wordpress-heroku/
sudo heroku --app create APP_NAME
sudo heroku addons:create heroku-postgresql
heroku pg:promote HEROKU_POSTGRESQL_INSTANCE
git push heroku

**Temas e plugins**
OceanWP
Ocean Extra
Elementor
WPForms Lite
WooCommerce
User Role Editor
Jetpack
User Menus
Super Socializer
https://www.youtube.com/watch?v=MakdGZdmmCQ <-Bonus
https://wordpress.org/plugins/user-role-editor/ <- Plugin Roles Editor
https://br.wordpress.org/plugins/theme-my-login/ <- Login Customer
</pre>
