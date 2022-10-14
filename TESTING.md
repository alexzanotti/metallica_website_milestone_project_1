# Testing

## Testing Procedure

Testing has been split into several sections. 

The first section of testing has been completed around validating that the user stories are met by the website.

Manual testing is the next section of testing - this is split between Functionality/Usability testing, which ensures that the website functions correctly are is useable by the user. The second part of manual testing to responsiveness testing - this ensures that the responsive design of the website is working correctly.

The next section of testing is automated testing - this looks at validating that the code itself is free from errors using.

Browser testing is the next section of testing - this ensures that the website functions in multiple browsers.

Finally, a Lighthouse Report is produced for each page of the website.

### User Story Testing

#### As a Metallica fan, I want to see images of the band throughout the years.
* A gallery page has been setup that displays images of the band
* The gallery is split by decade

#### As a Metallica fan, I want to watch interviews of the band, to know the band beyond just the music
* The Media page contains 3 videos embedded from youtube that are interviews with the Metallica band.

#### As a metal fan, I want to listen to audio samples of the band, to see whether i like the music 
* On the Media page, there are 6 audio elements, that play 30 seconds of the bands most popular songs.

#### As a metal fan, I want to watch live music videos of some of the most popular songs
* On the Media page, there are 3 videos embedded from youtube of live music videos.

#### As a user interested in learning more about Metallica, I want to have basic information about the band
* The home page of the website contains a section providing information about the band (this is sourced from Wikipedia).

#### As a user interested in learning more about Metallica, I want to view information about the band members
* The website contains a band members page, which provides basic facts about both current and previous band members.


### Manual Testing

#### Functionality & Usability

The following screenshots demonstrate functionality and usability of the website:

##### Navigation Bar 
![alt text](assets/testing-files/functionality/home-hover.png "Header Hover")
![alt text](assets/testing-files/functionality/home-hover-link.png "Header Hover")
![alt text](assets/testing-files/functionality/gallery-hover.png "Header Hover")
![alt text](assets/testing-files/functionality/gallery-hover-link.png "Header Hover")
![alt text](assets/testing-files/functionality/members-hover.png "Header Hover")
![alt text](assets/testing-files/functionality/members-hover-link.png "Header Hover")
![alt text](assets/testing-files/functionality/media-hover.png "Header Hover")
![alt text](assets/testing-files/functionality/media-hover-link.png "Header Hover")

##### Social Links
![alt text](assets/testing-files/functionality/facebook-icon.png "Facebook Icon")
![alt text](assets/testing-files/functionality/facebook-link.png "Facebook Link")
##### Twitter Link
![alt text](assets/testing-files/functionality/twitter-icon.png "Twitter Icon")
![alt text](assets/testing-files/functionality/twitter-link.png "Twitter Link")
##### Instagram Link
![alt text](assets/testing-files/functionality/instagram-icon.png "Instagram Icon")
![alt text](assets/testing-files/functionality/instagram-link.png "Instagram Link")
##### Youtube Link
![alt text](assets/testing-files/functionality/youtube-icon.png "Youtube Icon")
![alt text](assets/testing-files/functionality/youtube-link.png "Youtube Link")

##### Sitemap Link
![alt text](assets/testing-files/functionality/home-icon.png "Sitemap Hover")
![alt text](assets/testing-files/functionality/home-icon.png "Sitemap Hover")
![alt text](assets/testing-files/functionality/gallery-icon.png "Sitemap Hover")
![alt text](assets/testing-files/functionality/gallery-icon.png "Sitemap Hover")
![alt text](assets/testing-files/functionality/members-icon.png "Sitemap Hover")
![alt text](assets/testing-files/functionality/members-icon.png "Sitemap Hover")
![alt text](assets/testing-files/functionality/media-icon.png "Sitemap Hover")
![alt text](assets/testing-files/functionality/media-icon.png "Sitemap Hover")

##### Video Plays
![alt text](assets/testing-files/functionality/video-play.png "Video Plays")

##### Audio Plays
![alt text](assets/testing-files/functionality/audio-play.png "Audio Plays")


#### Responsiveness 

A number of aspects of the website were designed to be responsive to the users device - below are screenshots showing the area in scope (Header etc.) and the design for the various breakpoints. This was completed using Media queries and the bootstrap framework.

#### Header
##### Large
![alt text](assets/testing-files/responsiveness/header-large.png "Header Large")
##### Small
![alt text](assets/testing-files/responsiveness/header-small.png "Header Small")

#### Footer
##### Large
![alt text](assets/testing-files/responsiveness/footer-large.png "Footer Large")
##### Small
![alt text](assets/testing-files/responsiveness/footer-small.png "Footer Small")

#### Members
##### Large
![alt text](assets/testing-files/responsiveness/members-large.png "Members Large")
##### Small
![alt text](assets/testing-files/responsiveness/members-small.png "Members Small")

#### Gallery
##### Large
![alt text](assets/testing-files/responsiveness/gallery-large.png "Gallery Large")
##### Medium
![alt text](assets/testing-files/responsiveness/gallery-medium.png "Gallery Medium")
##### Small
![alt text](assets/testing-files/responsiveness/gallery-small.png "Gallery Small")

#### Audio
##### Large
![alt text](assets/testing-files/responsiveness/media-large.png "Audio Large")
##### Medium
![alt text](assets/testing-files/responsiveness/media-medium.png "Audio Medium")
##### Small
![alt text](assets/testing-files/responsiveness/media-small.png "Audio Small")


### Automated Testing
The W3C Markup Validator service was used to validate the HTML and CSS code used.

Below are screenshots showing each page of the project passing the validation checks.

### style.css
![alt text](assets/testing-files/automated/css-validation.png "style.css")
### index.html
![alt text](assets/testing-files/automated/index-validation.png "index.html")
### gallery.html
![alt text](assets/testing-files/automated/gallery-validation.png "gallery.html")
### members.html
![alt text](assets/testing-files/automated/members-validation.png "members.html")
### media.html
![alt text](assets/testing-files/automated/media-validation.png "media.html")

### Browser Testing

#### Chrome
* The Media page of the website is working correctly in Google Chrome
![alt text](assets/testing-files/browsers/chrome.png "chrome browser")
#### Firefox
* The Home page of the website is working correctly in Firefox
![alt text](assets/testing-files/browsers/firefox.png "firefox")
#### Edge
* The Band Members page of the website is working correctly in Edge
![alt text](assets/testing-files/browsers/edge.png "edge")
#### Safari
* The Gallery page of the website is working correctly in Safari
![alt text](assets/testing-files/browsers/safari.png "safari")

### Lighthouse Report

#### Home Page
![alt text](assets/testing-files/lighthouse/home.png "home page lighthouse report")
#### Gallery Page
![alt text](assets/testing-files/lighthouse/gallery.png "members.html")
#### Band Member Page
![alt text](assets/testing-files/lighthouse/members.png "members.html")
#### Media Page
![alt text](assets/testing-files/lighthouse/media.png "members.html")