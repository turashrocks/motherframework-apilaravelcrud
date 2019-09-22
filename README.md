![postman-seeklogo com](https://user-images.githubusercontent.com/25128254/65383480-f8493d80-dd37-11e9-9a40-4ca0063cd565.jpg)

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
## Rest API GET, POST, PUT with Postman

###### Register User [http://127.0.0.1:8000/api/register]

![register](https://user-images.githubusercontent.com/25128254/65382814-583ae680-dd2e-11e9-9575-e05f75a3f198.png)

###### To Login User. [http://127.0.0.1:8000/api/login] Keep track of the access_token received

![github1](https://user-images.githubusercontent.com/25128254/65382751-62a8b080-dd2d-11e9-9ae8-7ee1a9e8a65a.png)

###### To Get All tasks for the logged in users [http://127.0.0.1:8000/api/tasks]

![github2](https://user-images.githubusercontent.com/25128254/65382778-c4691a80-dd2d-11e9-815b-51034fd7e58a.png)

###### To Store Data we need to Edit the 'Header' as well as 'Body' in the url [http://127.0.0.1:8000/api/tasks] we are sending. Marked with Red Circle Below 

![store](https://user-images.githubusercontent.com/25128254/65383304-5e809100-dd35-11e9-812c-cacddcc4416a.png)

###### To Edit how the data is to be received in the API end we can edit TaskResources



Special Thanks to webdevmatrics youtube channel





###### Have some works to do still. But rather than following the whole tut its better to work on this <br/>

