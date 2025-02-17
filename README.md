# PHP_LARAVEL Comand
```
` ````````````
laravel new app
   _                               _
  | |                             | |
  | |     __ _ _ __ __ ___   _____| |
  | |    / _` | '__/ _` \ \ / / _ \ |
  | |___| (_| | | | (_| |\ V /  __/ |
  |______\__,_|_|  \__,_| \_/ \___|_|
 Would you like to install a starter kit? [No starter kit]:
  [none     ] No starter kit
  [breeze   ] Laravel Breeze
  [jetstream] Laravel Jetstream
 > breeze
breeze
Would you like dark mode support? (yes/no) [no]:
 >


 Which testing framework do you prefer? [Pest]:
  [0] Pest
  [1] PHPUnit
 > 0
0
php artisan serve // route
php artisan route:list //show all routing
php artisan route:list --except-vendor //show route
```
Create database Table
```
php artisan migrate


php artisan config:clear
php artisan cache:clear
php artisan view:clear


 php artisan tinke
Psy Shell v0.12.7 (PHP 8.2.12 — cli) by Justin Hileman
> $user=new App\Models\User;
= App\Models\User {#6196}
> $user->password='password'
= "password"
> $user->password
= "$2y$12$SzlJ2DoMEJBAW6FRrrjhHObYPGVK.rXy4rINz17f/IhUiSEIiXBfi"



 php artisan make:policy

  What should the policy be named?
❯ JobPolicy

  What model should this policy apply to? (Optional):
❯ Job
Job

   INFO  Policy [D:\Languages\Learn-Laravel\pro\app\Policies\JobPolicy.php] created successfully.  

PS D:\Languages\Learn-Laravel\pro> 


PS D:\Languages\Learn-Laravel\pro> php artisan queue:work

   INFO  Processing jobs from the [default] queue.

  2025-02-05 18:54:50 App\Mail\JobPosted .......................................... RUNNING
  2025-02-05 18:54:57 App\Mail\JobPosted


node -v

npm -v

npm install

npm run dev

npm run build
```
Create a new table
```
php artisan make:migration 'table name'

 php artisan migrate

```
Rename table
```
php artisan migrate:fresh

```
For creating any help
```
php artisan help 'make:Model' or 'anything'
