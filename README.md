# Wordpress Skeleton

Custom skeleton to use wordpress with git and composer

## Install

```
# Install composer
bash install-composer
# Install dependencies
php composer.phar install
# you can use instead local-config.sample.php
cp production-config.sample.php production-config.php
vim production-config.php
```
You can generete the salt with this [Salt Generator].

When you open your worpdress the first time, **you will need to install a theme and activate the installed packages if you wanna use any not admin page.**

## Custom Paths

 * **Admin:** your-site-url/wp/wp-admin
 * **Wordpress Content (plugins, themes, ...):** public/wp-content

## Install Wordpress Packages With Composer

You can search new wordpress packages on [wpackagist.org] and install them using like this:

```
# 'wpackagist-plugin/amp' is just and example
composer require wpackagist-plugin/amp
```

## License
[MIT]

[Salt Generator]: <https://api.wordpress.org/secret-key/1.1/salt/>
[wpackagist.org]: <https://wpackagist.org>
[MIT]: License
