# Aura Air


Aura Air is an Alexa skill that allows users to obtain information about air quality, amongst other things. Specifically, it can:

  - Get air quality in a home city on any given day
  - Get air quality in a user-chosen city on any given day
  - Get information about specific air pollutants, and what health effects they cause
  - Get the specific levels of air pollutants present on a given day
  - And more (if you search hard enough...)

# Demo Limitations
The demonstration has limitations as described here
  - Only two cities are stored in data, that being Sydney and Beijing
  - Only two data sets are used for each city; although all are retreived dyanmically, they are picked at random to simulate changes.

However, these limitations are set so that the demonstration may work without any other input. It does not need these limitations to function if data sets are provided by those developing these skills further.


### Installation
For NASA Spaceapps Sydney 2019, this was hosted on an Alexa-Supported Node.JS server. All data/media files were stored on an AWS S3 bucket.

To install, first paste the contents of 'interactionmodel.json' into Alexa's JSON editor. Then, install your media and data files to an AWS S3 bucket of your choosing, and keep the S3 bucket URL. Finally, paste the contents of 'index.js', 'package.json' and 'util.js' into their respective files.

### Videos of operation
The follow links below provide video demonstrations of the Alexa skill in operation.

Startup, City Selection, Home City Air Quality and Selected City Air Quality: https://1drv.ms/v/s!AgpCVugy6y7Vsth1WlkbuUUBTt3ifA?e=9Shw6V

Air Pollutant Information, Health Risks and Specific Amount Calculated: https://1drv.ms/v/s!AgpCVugy6y7Vsth7v58ICy5TgrDIhQ?e=6QdCD5

Air Pollutant Breakdown: https://1drv.ms/v/s!AgpCVugy6y7Vsth3Qrq63g_CNYtJlA?e=Lg11bs

Something Fun: https://1drv.ms/v/s!AgpCVugy6y7Vsth8xa4_kSrgvcv2jw?e=UEOYFb

License
----

NOSA


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
