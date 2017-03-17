# Performance matters - Bootstrap Documentation Site Optimization

## Settings
* Chrome Dev Tools - Network Throttle @ 2G Regular Speed
* Caching Disabled

### Stats

Stats BEFORE optimization
* Size: 1.2MB
* DOM Content Loaded @ 19.38s
* Full load @ 41.56s

Stats AFTER optimization
* Size: 242KB
* DOM Content Loaded @ 7.91s
* Full load @ 8.90s

![After optimizations](https://raw.github.com/SadisticSun/performance-matters/master/readme_img/screen.png?raw=true)

![Pagespeed score](https://raw.github.com/SadisticSun/performance-matters/master/readme_img/pagespeed1.png?raw=true)

![Pagespeed score](https://raw.github.com/SadisticSun/performance-matters/master/readme_img/pagespeed2.png?raw=true)

### Changes made
* Compressed IMG with TinyJPG
* Changed IMG to WEBP
* Used CDN for jQuery
* Added critical CSS
* Concatenated & minified CSS into 'docs.css'
* Enabled GZIP compression for Express with middleware
* Minified 'bootstrap.css' to 'bootstrap.min.css'

