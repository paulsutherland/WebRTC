## The Software Society

### July 2014

Note:
1. Society Introduction


# Who am I

* Paul Sutherland
* Construction Surveyor at Black & Veatch
* Moved across to Application deployment
* Working on mobile app development
* Member of Software Society since its formation in 2011
* mail@paulsutherland.net


# WebRTC

* What it is
* How you can use it
* Technical challenges
* Browser woes


# Motivation

* Dive in to understand what the technology is
* Do a talk to bring everyone here up to speed
* Use it in my web projects
* Have fun with leading edge technology


## Let's Get in our Time Machine

### Back to 1994ish
<!-- .slide: data-background="img/time-machine.jpg" -->


##### When the web was young
![When the web was young](img/time.jpg)


##### When the web was a hypertext driven page centric design
![When the web was young](img/first-page.png)


##### Things were simple looking
![When the web was young](img/yahoo.png)


##### Moving forward 1998
![When the web was young](img/bbc.png)


##### We were still dominated by page centric design
![When the web was young](img/google.png)


#### Then through the early to mid 2000s we became dynamic


#### The term "Web 2.0" was first used in January 1999 by Darcy DiNucci


"The Web we know now, which loads into a browser window in essentially static screenfuls, is only an embryo of the Web to come. The first glimmerings of Web 2.0 are beginning to appear, and we are just starting to see how that embryo might develop. The Web will be understood not as screenfuls of text and graphics but as a transport mechanism, the ether through which interactivity happens. It will [...] appear on your computer screen, [...] on your TV set [...] your car dashboard [...] your cell phone [...] hand-held game machines [...] maybe even your microwave oven".
<!-- .element: style="  text-align: left; font-style: italic; font-size: 20px; margin: 10px;" -->

###### https://en.wikipedia.org/wiki/Web_2.0



## Web 2.0


##### We we are interacting with the data without chasing links
![When the web was young](img/maps.jpg)


##### We start to feed the machine
![When the web was young](img/youtube.png)


##### Giving birth to the Social web
![When the web was young](img/facebook.jpg)



## What Next?


# Welcome to the Real Time Web

<!-- .slide: data-background="img/real-time.jpg" -->


### A world where through the browser you can:

* File Share
* Live Chat
* Sensor Feeds
* Data Feeds
* Screen Sharing
* Gaming


### All Peer to Peer


### Browser Support
* Chrome 23
* Firefox 22
* Opera 18


### Mobile Support 
* Chrome 28
* Firefox 24
* Opera Mobile 12


### Apple
* Not supporting it
* They are very silent on it
* They would need to replace the VP8 codec with H.264
* Replace Opus voice codec with AAC-LD


### Microsoft
* Have an alternative called CU-RTC-Web
* Stands for: Customizable, Ubiquitous Real-Time Communication
* Looking at a lower level API 


<!-- .slide: data-background="img/webrtc-ready.png" style="background: none;" -->


### Interoperability between browsers
* Firefox Beta post May 2013 
* Opera 20 
* Chrome 25 are interoperable


###### API Differences 
<!-- .element: style="font-weight:bold;" -->

|W3C Standard          | Chrome                   | Firefox                 |
|--------------------- | :-----------------------:| -----------------------:|
|getUserMedia          |  webkitGetUserMedia      | mozGetUserMedia         |
|RTCPeerConnection     |  webkitRTCPeerConnection | mozRTCPeerConnection    |
|RTCSessionDescription |  RTCSessionDescription   | mozRTCSessionDescription|
|RTCIceCandidate       |  RTCIceCandidate         | mozRTCIceCandidate      |
<!-- .element: style="font-size:20px; margin:0 auto;" -->


<!-- .slide: data-background="img/chrome-flags.png" style="background: none;" data-background-size="80%" -->


<!-- .slide: data-background="img/firefox-about.png" style="background: none;" data-background-size="80%" -->