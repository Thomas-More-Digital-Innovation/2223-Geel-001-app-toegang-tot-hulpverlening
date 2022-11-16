# Mobile app development

## Information
For this project I'll be creating a mobile application. Therefor I'll need some kind of mobile app. dev. tool.
In this document I will compare some of the most used ones and make a decision on which of these tools I will use for my project.

This will be my first mobile app. so most of the frameworks/tools will be new to me.
Therefore I will look for a framework/tool that is both user-friendly for beginners but that also gives me all functionalities that I might need for this project.

---

## Where to start? 
Before I actually start comparing frameworks/tools I need to know what to look for.
To give myself a better understanding about this, I will first watch some video's about choosing the right tool/framework for beginning mobile app. developers.

The question is: **What technology will I use for creating the app?**

Main choices are:
* first party apps
* PWA
* Cross-platform native apps

I found this video: [Choosing the best mobile app framework](https://www.youtube.com/watch?v=4m7msadL5iA) from the [Microsoft for Startups](https://www.youtube.com/c/MicrosoftforStartups) YouTube channel very helpful in giving me this basic knowledge and helped me in answering the question I stated above. 

### Information from this video ([Choosing the best mobile app framework](https://www.youtube.com/watch?v=4m7msadL5iA))
#### First party native apps
* Apple 
  * makes IOS
  * makes Xcode development toolkit 
    * Used to create native IOS apps in Objective C and Swift code
* Google
  * makes Android
  * makes Android Studio development toolkit
    * Used to create native Android apps in Java and Kotlin
* Good/bad things of first party apps
  * POS. native UI/UX
  * POS. Performance
  * POS. Support
  * NEG. development speed (can't use same code for both platforms)
  * NEG. not open source
  * NEG. maintenance cost

#### Progressive web apps (PWA)
* Website that is running locally on a device
* You can make use of web. frameworks (React, AngularJS, ...)
* Good/bad things of Progressive web apps
  * POS. repurpose web dev. skills
  * POS. does not require App store 
  * POS. development speed (code is useable on both platforms)
  * NEG. UI/UX (recreate same look and feel of Android/IOS apps)

#### Cross-platform native apps
* Frameworks for creating native apps on both platforms which includes access to all Android/IOS API's
  * POS. development speed (code is useable on both platforms)
  * POS. low maintenance cost   
  * Example: Xamarin(Microsoft)
    * Build in Visual Studio using .NET (C#, F#)
    * POS. UI/UX native to device 
    * POS. development speed
    * POS. performance
    * POS. open source
  * Example: React native(Facebook)
    * Build in Visual Studio using JavaScript
    * POS. UI/UX native to device 
    * POS. development speed
    * POS. performance
    * POS. open source
  * Example: Flutter(Google)
    * Build in IntelliJ, Android Studio and VS Code using Dart (comparable to Java and C#)
    * POS. Performance (bespoke method of UI/UX)
    * POS. Open source
    * NEG. relatively new compared to the other ones
    * NEG. no native UI/UX

#### Use case scenario to help choice (most simular to my project)
* Simple APP (existing website AngularJS, doesn't need many features) -> best choice PWA 

### What will I be using
**Since this project doesn't involve a very dynamic or feature rich app, I'm leaning most towards using a PWA**.

It's simple enough for non-IT people to understand how they need to link this to their mobile phone home page and a link to this PWA could easily be added to the already existing website of the city Geel.

---

## PWA: 
### Quick video for some basic knowledge and context
First of all I always like watching a [Fireship](https://www.youtube.com/c/Fireship) about the subject. <br>
These short (typically 100 second) video's are great at getting a basic overview and give you some basic knowledge. <br>
So for this subject, I've watched the [Progressive Web Apps in 100 Seconds // Build a PWA from Scratch](https://www.youtube.com/watch?v=sFsRylCQblw) video. <br>
This video is a little longer since it also explains how to create a basic PWA.

### Useable links:
1. [PWA asset generator](https://github.com/elegantapp/pwa-asset-generator/releases)
2. [Hack news PWA's](https://hnpwa.com/)'
3. [Everything about PWA, web API's, etc](https://web.dev/)
4. [PWA tutorial with ReactJS](https://www.youtube.com/watch?v=bRoRikxgIew&list=PL8p2I9GklV46NFHdQMFBjXvxwVqtJpa2N)
5. [PWA tutorial with HTML,CSS,Javascript and Firebase font-end and back-end](https://www.youtube.com/watch?v=4XT23X0Fjfk&list=PL4cUxeGkcC9gTxqJBcDmoi5Q2pzDusSL7)
6. [PWA with tailwind CSS](https://www.youtube.com/watch?v=BKHHbQ-mVEM)




