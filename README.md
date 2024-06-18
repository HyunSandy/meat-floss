RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://Hyunsandy.github.io/meat-floss/index.html$1 [R,L]
