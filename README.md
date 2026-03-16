<p align="center">
  <img src="https://avatars.githubusercontent.com/u/62794249?v=4" style="width: 100px; border-radius: 100%;">
</p>

<h1 align="center">SecretSheppy</h1>

I am primarily a full stack web developer, with desktop app development experience in nw.js. I have significant experience in JavaScript (pure, jQuery and node), HTML and CSS. I thoroughly enjoy exploring new languages. My current favourite language is go (Golang) and I am currently working on several projects in go.

## My Pages Deployments

Occasionally I write something useful which I then host on GitHub pages. These projects are linked below.

### String of cards to Unicode playing cards

Takes a string of playing cards formatted as `Card {value=Two, suit=Diamond}` and converts it into a string of Unicode playing cards.

* [view deployment](https://secretsheppy.github.io/text-to-playing-card/)
* [view source](https://github.com/SecretSheppy/text-to-playing-card)

### Array of points to equation of a circle (Least Square Circle)

Calculate the equation of the circle of best fit from an array of larger that three points. The user can disable certain points, and the equation history is tracked, allowing the user to see how different points affect the result.

* [view deployment](https://secretsheppy.github.io/circle-data-from-points/)
* [view source](https://github.com/SecretSheppy/circle-data-from-points)

## My Repositories

My main repositories that I feel are useful enough to be publicly released are listed below. Some of these are much, much older than the commit history would have you believe so the code quality is not always the best. The development of all the below projects significantly contributed to my journey to advance as a developer, each teaching me several new things about integral structure of programs, working in teams or leaning a language.

### Heather4Java

The fourth iteration of my Heather game engine, built in Java with the JOGL OpenGL bindings for a university 3D project. The design is based loosely off of my experience with Unreal Engine. It allows for loading of 3D object files, texturing, animations (via a custom animation language) and a variety of other things. It is not a hugely advanced game engine, but given enough time you could definitely build some cool things by using it as a launchpad to build off of. It was very, very fun to develop. I particularly enjoyed making under the hood performance improvements as the engine got more complicated!

* [view source](https://github.com/SecretSheppy/heather4java)
* [get latest release](https://github.com/SecretSheppy/heather4java/releases/latest)

### ArmorPaint Cloud Content Manager

ArmorPaint Cloud Content Manager is a command line application for downloading, updating, and removing the cloud resources for ArmorPaint on your local machine. I built it after I tried and failed to use the cloud textures when experimenting with the ArmorPaint 3D texture painting tool due to an error in the application.

* [view source](https://github.com/SecretSheppy/armorpaint-cloud-content-manager)
* [get latest release](https://github.com/SecretSheppy/armorpaint-cloud-content-manager/releases/latest)

### Haskedit

Haskedit is my most recent attempt at a "proper" desktop application. It is a text editor for Haskell on windows that provides all the basic essentials whilst also being relatively light weight in terms of memory usage. I built Haskedit as I was required to use Haskell for a recent project and I felt that there were no editors that provided the experience I wanted to work with.

* [view source](https://github.com/SecretSheppy/haskedit)
* [get latest release](https://github.com/SecretSheppy/haskedit/releases/latest)

### Ciphershare

Ciphershare is an encrypted filesharing website that I built with three friends at a 24 hour hackathon. It is built in go using the gorilla web framework. I was the only person on the team with go experience, so working in the team was a fun and rewarding challenge.

* [view source](https://github.com/SecretSheppy/ciphershare)
* [get latest release](https://github.com/SecretSheppy/ciphershare/releases/latest)

### NX1C web forum

A pure PHP reddit like forum service. I built it because I was interested to see what a pure PHP service would be like in a world where new services are now almost exclusively being developed in advanced web frameworks (I'm discounting WordPress 🤣). I found this was a fun side project and PHP was a lot more interesting that I had anticipated (though having to use the `$` to name every variable is very **very** tedious. I also developed an "ORM" like syntax for generating SQL statements (as I was using a direct SQL connection).

* [view source](https://github.com/SecretSheppy/nx1c-web-forum)

### Go Snake

Go Snake is an implementation of the classic snake game in go, but the game plays itself. This is a re-implementation of a project I wrote in C++ a long time ago that I wrote whilst learning go to test my knowledge.

* [view source](https://github.com/SecretSheppy/go-snake)

### NX1C private chat

A decentralised end to end encrypted messaging service. The default encryption provided by this project is terrible, but I wrote it to try out making an encryption algorithm (with no research 🤦‍♂️). That being said, I knew that would turn out to be the case so I developed the app with a standard encryption interface, so end users could just swap out the default encryption package for a custom one with very little trouble.

* [view source](https://github.com/SecretSheppy/nx1c-private-chat)

### Open Explorer

Open Explorer is a project I will one day revisit and revitalise. I built Open Explorer because I really like the Windows File Explorer experience, and I wanted to create a file browser that would give the same experience on all platforms. I did achieve this goal but I had not planned this project, so I ended up with a very inefficient core structure and consequently relatively poor code quality. This project is much older than when I committed it to GitHub.

* [view source](https://github.com/SecretSheppy/open-explorer)

## My Guides

I occasionally write guides to help clarify things that may be helpful to other developers, particularly those who are looking to get started with something new.

### Using JOGL (Java OpenGL) with IntelliJ

I wrote this guide because I was using [JOGL](https://jogamp.org/jogl/www/) for a university module. We were instructed to use the JAR version of the library, and getting this setup in JetBrains is not the most straightforward process. This guide brings together all the resources I found I needed to accomplish this and presents instructions along with visual aids for clarity.

* [view source](https://github.com/SecretSheppy/jogl-with-jetbrains-ides)
