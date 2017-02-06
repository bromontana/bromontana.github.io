---
layout: post
background: ../../../assets/background.png
---

# New Year New Projects

And I bet it is going to be a good one!


## My Weak Excuse

I haven't updated the blog in a little while but it is because I have been crazy busy and
every time that I want to work on a post I come up with a new one and I start working on that
one so I don't forget it. I apologize for that but here is a quick synopsis of what I have
been working on!

## My New Project

SO what I have been working on is a little IoT (or Internet of Things) projects. The quick
summary is: this project's aim is to create affordable, and powerful "SmartHome" functionality
while up-cycling obsolete technology.


All projects are supposed to solve some problem and result in some kind of reward. One
example when you build a house the problem is that someone needs that home and they will
pay for it. Another is if you are hungry the project will be making a sandwich and the
reward will be eating.


### What's the Problem?

In this case there are two problems that I want to address. The first problem is everyone wants a
cool/futuristic "SmartHome" but companies are not trying very hard to deliver. People like to ask
me "hey Frank, what does make a SmartHome?" I usually tell them this: Think about what "SmartHome"
devices they can think of that exist commercially right now. Typically something like this comes to mind.

![Amazon Dot]({{ site.url }}/assets/IoT/alexa_dot.gif)

\\
Why do I think that this _isn't_ the way of the future home? This is a product of
vertical integration. Vertical integration is when a company combines several stages or
products all together. Services like Alexa are good if you are Amazon, because it forces people who want
use your product to also use your other services because it's easy.


## What's the OTHER Problem?

The second problem is a little more out there. Because of the nature of my university I have
taken a lot of classes that are tied to sustainability. This makes me think about how wasteful
many of the commercial practices in our country are. One that haunts me the most is how terrible
our phone culture is. So much so that we assume that most phones are obsolete after two years, or replace
an entire device when the screen breaks even though all of the components on the inside (the parts that are
actually difficult to replace) are still in-tact. There are plenty of other reasons that I dislike
the way phones are manufactured and disposed of (use of rare earth metals + poor mining practices, no
solid infrastructure for recycling electronics, no good methods of disposing batteries, etc.) however
despite all of these what I dislike the most is the lack of acknowledgement that the sensors in phones
receive. There is a wide array of sensors mounted on phones that most people cannot appreciate.



## How Does This Project Fix It?(!)?

This project that I am working on will [upcycle](https://en.wikipedia.org/wiki/Upcycling) old phones and
take advantage of their robust hardware, while also giving phones a second wind to help them stay out
of landfills. The project will also explore using the existing "SmartHome" voice service
([Alexa](https://developer.amazon.com/alexa-voice-service)) as a secondary UI. The primary UI of this
"SmartHome" is going to be based on face detection and recognition.

![Here is the first working face recognition]({{ site.url }}/assets/IoT/FaceRec/franks_face_one.png)

The main idea is that the phones will be able to remember faces, and associate them with data about the
person. One example of how this can work is when you walk in and ask the phone to play some music, it could
automatically direct itself to that person's favorite playlist. This (in theory) is all possible
all it requires is some love and care and a lot of hours learning how to efficiently mount debian over
android on different devices made by different manufacturers. Oh and on top of all that make sure they can
quickly communicate over a network and share a secure database, but also be able to quickly and effectively
take images of a person, prepare those images, and use a lot of [fancy math](http://disp.ee.ntu.edu.tw/~pujols/Eigenfaces%20and%20Fisherfaces.pdf)
to create reusable references for those faces.

## So What's Next?

In a nutshell, what I have done is:

+ Gotten OpenCV to work for face detection and learn about how face recognition works
+ [Rooted](http://www.androidcentral.com/what-does-rooting-your-phone-actually-mean) a phone and found a way to mount debian on top of a custom android ROM
+ Have a plan to make some money and try to make a business out of this project so I can pay people to help me iron it out later

\\
And what I have left to do is:

+ Successfully run OpenCV on the phone's debian
+ Register the phone as a device with the Alexa Voice Service and learn how to use AVS
+ Create a program that will take a series of pictures upon request and crop the face well enough
to make a model that can be referenced for face recognition dynamically
+ Find some real applications for the nodes (or phones on the network)
+ Get the nodes to communicate efficiently
+ Decide on where the database will be stored and how it will be structured
+ Deploy a working prototype

\\
When I look at this list of things that are left for me to do I have to admit it is a little intimidating,
however I hope that in the next couple months I will assemble a team of talented people who can
help me build this into a functional prototype that I can one day pitch. 
