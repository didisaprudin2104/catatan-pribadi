# 🗒️ catatan-pribadi

Kumpulan catatan pribadi tentang hal-hal yang pernah saya kerjakan, pelajari, atau eksplorasi secara teknis maupun non-teknis.

---

## 📌 Daftar Catatan

### ✅ [Deployed OpenVPN on Google Cloud Platform (GCP)](catatan-gcp/openvpn-gcp.md)
📅 16 April 2025  
🚀 Menyusun langkah-langkah lengkap untuk menginstal dan menjalankan OpenVPN di VM instance Google Cloud — dari setup awal sampai testing koneksi.

---

## 📁 Golang
go mod init blog
go get -u github.com/go-sql-driver/mysql
go run main.go

## 📁 Mobile dengan Ionic atau dengan capasitorJS laravel
https://ionicframework.com/docs

## 📁 ONO
https://s.id/free-owp-ebooks

##.htaccess Laravel
<IfModule mod_rewrite.c>  
RewriteEngine On  
RewriteBase /  
#Loading PHP as if is public/ from /  
RewriteRule ^$ public/index.php [L]  
#Loading page as if is public/ from /  
RewriteRule ^((?!public/).*)$ public/$1 [L,NC]  
  
RewriteRule (^\.|/\.) - [F]  
  
<FilesMatch "^(\.env\.example|artisan|package\.json|README\.md|readme\.md|composer\.json|composer\.lock|LICENSE|spark|\.env|\.gitignore|builds|phpunit\.xml\.dst|preload\.php)$">
        Require all denied
    </FilesMatch>

  
</IfModule>

