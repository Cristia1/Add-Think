1 fii atent la fiserul il cauti  .env si acolo sa ai asa 
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=Proiect
DB_USERNAME=root
DB_PASSWORD=


apoi dai asta in terminal   
  1 composer install
2 cp .env.example .env
3 php artisan key:generate
4 php artisan migrate
si ca sa mearga aplicatia sa o vezi dai asa php artisan serve

