# PHP-Laravel
php server command ---- php -S localhost:port -t your_folder/

# Valet-Ngrok Problem
brew install ngrok
cd ~/.composer/vendor/laravel/valet/bin
./ngrok authtoken [yourtoken]
cd [back to your laravel proj]
valet share
