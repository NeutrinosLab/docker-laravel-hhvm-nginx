#docker-laravel-hhvm-nginx

A super fast, production hardened HHVM / PHP-7 `Dockerfile` served by Nginx forward proxy. See [link](http://goo.gl/Adqu0i) for the why. Perfect for horizontally distributed `Laravel` applications run within a Docker container cluster.

**Note** due to issues with Boot2Docker and VirtualBox response times on a local environment (with these tools) is slightly degraded with local volumes enabled.

**Note** Installs [hirak/prestissimo](https://github.com/hirak/prestissimo) composer parallel install plugin. If you have issues with composer installs remove this plugin.

## Stack

* **HHVM** (Facebooks PHP-7 runtime)
* **Nginx** (FastCGI web-server)
* **Composer** (PHP package manager)
* **PHPUnit** (PHP unit testing)
* **Laravel** (Installs laravel command line)


This image is based on [andrewmclagan/nginx-hhvm-docker](https://github.com/andrewmclagan/nginx-hhvm-docker)

