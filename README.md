# Docker-Laravel
 Docker Laravel Composer  Nginx PHP8 Postgresql pgAdmin

 github üzerinde bulunan projemizi indiriyoruz.
 projemizin ana klasörüne girip laravel'i src klasörünün içine kuruyoruz. 
 "src klasöründe text.txt varsa siliniz"

 >    composer create-project laravel/laravel src

 daha sonra docker container 'ımızı ayağa kaldırıyoruz.

 >    docker-compose up -d


 docker container kurulup ayağa kalktıktan sonra localhost yazıp projemizi açabiliriz.


Ek Bilgiler:

DockerFile içinde php8.2 ve composer kurulumu için komutlar bulunmaktadır.

php laravel için kullanacağımız temel extension lar yine dockerfile içinde bulunmaktadır.

Nginx url yönlendirme komutlarıda default.conf dosyasında bulunmaktadır.
  
  
github linki :https://hkmsmart.blogspot.com/2024/07/docker-laravel-compose.html
