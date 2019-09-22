# motherframework-apilaravelcrud
MotherFramework series Laravel Rest API Toekn Based Login and CRUD Generation. <br/> 
Template to be used for future

## Installation

###### git clone full repo 
###### .env file modifcation

```
composer install
```

```
php artisan migarate
```

```
php artisan key:generate
```

```
php artisan passport:install 
```

```
php artisan vendor:publish --tag=passport-migrations
```

## Generating Demo Contents

```
php artisan tinker
```
###### In command line type  

```
factory(App\Task::class, 5)->create()
```
## Login api contents by Postman

![github1](https://user-images.githubusercontent.com/25128254/65382751-62a8b080-dd2d-11e9-9ae8-7ee1a9e8a65a.png)

## Get All tasks for the logged in users configuration

![github2](https://user-images.githubusercontent.com/25128254/65382778-c4691a80-dd2d-11e9-815b-51034fd7e58a.png)









###### Have some works to do still. But rather than following the whole tut its better to work on this <br/>

