# Kebook AGC Books
## Installation

### 1. Uploads
- Upload `kebook` folder outisde public_html/public
- Upload `public` folder to your public directory `public` or `public_html`

**Example**

`/home/username/`

`-- logs`

`-- kebook`

`-- public_html`


### 2. Settings
- Open `app/config/kebook.php` to configure your site.
- Insert the license, base_url, sitename, etc.
- you can get the license from member area https://my.agcmastery.com

### 3. Running Your Site
- Open kebook directory `cd /home/username/kebook`
- Setting Permission for storage folder `chmod -R 777 storage`
- Install Composer `composer install`
- Install Node `npm install`
- Open `https://domain.com/api/v1/license/active` to activate your license.

## Customize

If you need to customize kebook like a logo, image,meta, etc.

you can found it on resource directory `kebook/resources`

`resources/images`

`resources/js`

`resources/views`

`resources/sass`

## Commands

`php artisan cache:clear` to clear cache file

`php artisan config:clear` to clear cache config

`php artisan view:clear` to clear cache template

`php artisan route:clear` to clear cache route


