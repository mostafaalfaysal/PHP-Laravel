# PHP-Laravel
php server command ---- php -S localhost:port -t your_folder/

# Valet-Ngrok Problem Fix



```bash
1. brew install ngrok
2. cd ~/.composer/vendor/laravel/valet/bin
3. ./ngrok authtoken [yourtoken]
4. cd [back to your laravel proj]
5. valet share
```
