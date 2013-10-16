# Map of US National Parks
*powered by Silex, PHP, MongoDB, and Leaflet maps*

To deploy a clone of this application using the [`rhc` command line tool](http://rubygems.org/gems/rhc):

    rhc app create parks php-5.3 mongodb-2.2 --from-code=https://github.com/ryanj/silex-mongodb-parks.git
    
Or [link to a web-based clone+deploy](https://openshift.redhat.com/app/console/application_type/custom?cartridges%5B%5D=php-5.3&cartridges%5B%5D=mongodb-2.2&initial_git_url=https%3A%2F%2Fgithub.com%2Fryanj%2Fsilex-mongodb-parks.git) on [OpenShift Online](http://OpenShift.com) or on [your own OpenShift cloud](http://openshift.github.io): 

    https://openshift.redhat.com/app/console/application_type/custom?cartridges%5B%5D=php-5.3&cartridges%5B%5D=mongodb-2.2&initial_git_url=https%3A%2F%2Fgithub.com%2Fryanj%2Fsilex-mongodb-parks.git

A demo is available at: [http://phparks-shifter.rhcloud.com/](http://phparks-shifter.rhcloud.com/)

## License
This code is dedicated to the public domain to the maximum extent permitted by applicable law, pursuant to CC0 (http://creativecommons.org/publicdomain/zero/1.0/)
