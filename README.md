
# Heroku Buildpack for WordPress

[![WordPress](https://raw.githubusercontent.com/ajaykumar127/PardotMaster/181a15d0a6dcc44dcd5083e2b01be762100579b4/heroku%2Bwordpress.png)](https://github.com/ajaykumar127/PardotMaster)

I've created a sample website that demonstrates how to build customer blog with [WordPress](http://www.wordpress.org) using its plugins [WP Google Analytics](https://wordpress.org/plugins/wp-google-analytics/), [All in One SEO Pack](https://wordpress.org/plugins/all-in-one-seo-pack/), [Amazon S3 and many more...](https://wordpress.org/plugins/amazon-s3-and-cloudfront/)

You can deploy your own version of WordPress running on MySQL on Heroku platform in seconds using the Heroku button below:

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/ajaykumar127/PardotMaster)

## Overview

```
└── public                 # Heroku webroot
    ├── content            # The wp-content directory. Renamed to content to avoid confusion with wp-content - and it looks prettier
    │   ├── plugins        # Plugins
    │   ├── mu-plugins     # Required plugins
    │   └── themes         # Your custom themes
    │
    └── wp                 # Where the actual WordPress install will be installed by Composer
