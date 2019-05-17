# Social Media Mashup
Version 1.0.0

## Contents
* Example page of filterable social media feeds for:
  * API - Facebook, Twitter, Instagram 
  * RSS - Pinterest, YouTube, Flickr, Blog/custom
* Data definition allows addition/removal of these feeds
* mashup.js controls all calls to APIs

Note: Twitter is currently having some issues and sometimes fails to load.

Current Site was exported using Cascade CMS 8.12.cloud1

## Updates
### v1.0.0
* Updated FontAwesome to v5.8.1
* Overall: facelift with new fonts, icons, color palette.
* Fixed Instragram feed by updating the Instagram API call.
* Updated Facebook API to the latest version (v3.2)
* Updated to latest Bootstrap 3 version (v3.4.1)
* Updated to latest minified jQuery version (v3.3.1)
* Added Pinterest via RSS
  * https://www.pinterest.com/<username>/feed.rss
  * https://www.pinterest.com/<username>/<board-name>.rss
* Updated data definition to configure social media platforms
