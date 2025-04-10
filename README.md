![alt text](/public/img/image.png)

## Project Installation

Follow these steps to set up and run the project locally.

### Requirements
- PHP
- Composer
- API Access Token from TMDb (https://www.themoviedb.org/documentation/api) (API Read Access Token (v4 auth))

### Installation steps:

```bash
git clone https://github.com/iammaga/Netflix.git
cd Netflix
```
```bash
composer install
```
```bash
cp .env.example .env
```
Open the .env file, find or add the variable TMDB_TOKEN, and replace YOUR_TMDB_TOKEN with your TMDb API token:
```bash
TMDB_TOKEN="YOUR_TMDB_TOKEN"
```
```bash
php artisan key:generate
```
```bash
php artisan serve
```
In your web browser, go to the address: http://localhost:8000.

