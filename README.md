[![Wordpress](images/wp-repo.png)](WordPress)
# WordPress

This package deploys an High Available WordPress hosting solution that contains 1 application server and 1 database container. The package provides vertical scalling per node and horizontal scaling for each layer out-of-the-box.

### Highlights
This package is designed to handle big load spikes by adjusting the allocated resources and topology configuration with a help of vertical and horizontal scaling. As result, it provides very cost effective solution for websites and blogs with variable load.

### Environment Topology

![wordpress-environment-topology](../images/word-press-environment-topology.png)

### Specifics

Layer                |     Server    | Number of CTs <br/> by default | Cloudlets per CT <br/> (reserved/dynamic) | Options
-------------------- | --------------| :----------------------------: | :---------------------------------------: | :-----:
AS                   | NGINX PHP FPM |       1                        |           1 / 16                          | -
DB                   |    MySQL      |       1                        |           1 / 16                          | -

* AS - Application server
* DB - Database
* CT - Container

**WordPress Version**: 5.1.1<br/>
**PHP Engine**: PHP 7.3.0<br/>
**MySQL Database**: 8.0.13

### Deployment

Take advantage of our 14 Day Free trial and get this solution instantly deployed, click the "Deploy to WebWolf Hosting" button, specify your email address within the widget, and press Install.

[![GET IT HOSTED](https://raw.githubusercontent.com/mommaroodles/wordpress/master/images/deploy-to-webwolf.png)](https://reg.cloud.webwolf.systems/?manifest=https://github.com/mommaroodles/wordpress/raw/master/manifest.jps)

To deploy this package to WebWolf PaaS, import [this JPS manifest](https://mommaroodles.github.io/wordpress/blob/master/manifest.jps) within your dashboard.




