# Film Platform
** This stanza needs manual review at [https://www.oclc.org/support/services/ezproxy/documentation/db/filmplatform.en.html](https://www.oclc.org/support/services/ezproxy/documentation/db/filmplatform.en.html) **

## Some of OCLC's notes for this stanza

Film Platform requires SSL configuration and the following database stanza in config.txt :

Title Film Platform
 URL https://filmplatform.net
 Host filmplatform.net
 Host https://www.filmplatform.net
 Host www.filmplatform.net
 DJ filmplatform.net

In order to access your institution’s Film Platform page, ensure that you construct your starting point URLs with your unique university Film Platform link as follows:

https://ezproxy.mylib.org/login?url=https://filmplatform.net/universities/uniqueID/

Where “unique ID” is provided by Film Platform.

To provide proxied links directly to films within your institution’s subscription, add your institution’s proxy prefix before the link to the film following the example below:

https://ezproxy.mylib.org/login?url=https://filmplatform.net/product/movieID/
