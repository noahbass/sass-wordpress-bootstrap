# (Sass) WordPress Bootstrap

Stuff you need to start a WordPress project with Bootstrap and Sass.

[Bootstrap](http://twitter.github.com/bootstrap) in Wordpress theme by [WordPress Bootstrap](https://github.com/320press/wordpress-bootstrap) which is based on [Bones](https://github.com/eddiemachado/bones) with the awesome addition of [sass-twitter-bootstrap](https://github.com/jlong/sass-twitter-bootstrap).

## Discrepancies from [WordPress Bootstrap](https://github.com/320press/wordpress-bootstrap)

* All `.DS_Store` files have been deleted and git ignored.
* `style.css` is no longer called in the `functions.php` (look below).
* LESS has been replaced by Sass...

## Discrepancies from [Sass Twitter Bootstrap](https://github.com/jlong/sass-twitter-bootstrap)

* Organized `.scss` files in a `partials` folder.
* New file added named `_wp.scss` with stuff from `style.css` (with exception to the theme information).
* Added a [`_shame.scss`](http://csswizardry.com/2013/04/shame-css/).