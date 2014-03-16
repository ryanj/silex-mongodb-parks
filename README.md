# Map of US National Parks
*powered by Silex, PHP, MongoDB, and Leaflet maps*

To deploy a clone of this application using the [`rhc` command line tool](http://rubygems.org/gems/rhc):

    rhc app create parks php-5.4 mongodb-2 --from-code=https://github.com/openshift-quickstart/silex-mongodb-parks.git
    
Or [link to a web-based clone+deploy](https://openshift.redhat.com/app/console/application_type/custom?cartridges%5B%5D=php-5.4&cartridges%5B%5D=mongodb-2&initial_git_url=https%3A%2F%2Fgithub.com%2Fopenshift-quickstart%2Fsilex-mongodb-parks.git) on [OpenShift Online](http://OpenShift.com) or on [your own OpenShift cloud](http://openshift.github.io): 

    https://openshift.redhat.com/app/console/application_type/custom?cartridges%5B%5D=php-5.4&cartridges%5B%5D=mongodb-2&initial_git_url=https%3A%2F%2Fgithub.com%2Fopenshift-quickstart%2Fsilex-mongodb-parks.git

A demo is available at: [http://phparks-shifter.rhcloud.com/](http://phparks-shifter.rhcloud.com/)

## Local Development

Fire up your own local development server with php-5.4 or better:

    php -S localhost:8080 -t static app.php 

## License
This code is dedicated to the public domain to the maximum extent permitted by applicable law, pursuant to CC0 (http://creativecommons.org/publicdomain/zero/1.0/)
