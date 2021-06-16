# MONITORY

## Versioonid, mis on hetkel kasutuses:
PHP 8.0.7
Laravel 8
Composer 2.1.3
Mysql  8.0.25
XAMPP 8.0.7 (Serverite haldamiseks ja andmebaasi nägemiseks)
Apache Web Server

## Installeerimine
Palun vaadake Laraveli dokumentatsiooni selle installeerimiseks, kui teil veel ei ole seda.

Järjekord: 
1. Andmebaasi loomine Xamppi: Käivita xampp, mine localhost/phpmyadmin. Tee uus andmetabel nimega “Monitory”, lisa githubis leiduva tekstfaili “Monitory_create.sql sisu SQL koodi genereerimise nupult??
2. Loo andmebaasiga ühendus läbi Laraveli: Mine .env faili, pane DB_host blabla jne, mis need seal kõik on.
Mine Public/config/database.php vms. Muuda seal db host vastavaks .env konfioguratsiooniga.
3. Nüüd mine konsooli ja vastavasse kausta, kuhu sul on pullitud meie githubi branch. Ava selles kasutas terminal ja kirjuta: “php artisan serve”. See paneb laraveli raamistiku jooksma ning annab sulle localhost aadressi, millelt saada meie lehti kuvada. Näiteks: aadress/home.
