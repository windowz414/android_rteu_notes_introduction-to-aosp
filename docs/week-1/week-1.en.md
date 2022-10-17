---
marp: true
theme: default
style: |
    img[alt~="center"] {
      display: block;
      margin: 0 auto;
    }
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://birchtree.nyc3.digitaloceanspaces.com/2021/materialyou/desktop/material_you_desktop_1.png')
header: 'Introduction to AOSP'
footer: ''
title: "Introduction to AOSP"
author: "Author: B. KURT"
date:
subtitle: "AOSP Introduction and History"
geometry: "left=2.54cm,right=2.54cm,top=1.91cm,bottom=1.91cm"
titlepage: true
titlepage-color: "FFFFFF"
titlepage-text-color: "000000"
titlepage-rule-color: "CCCCCC"
titlepage-rule-height: 4
logo: "assets/2021-10-19-15-01-36-image.png"
logo-width: 100 
page-background:
page-background-opacity:
links-as-notes: true
lot: true
lof: true
listings-disable-line-numbers: true
listings-no-page-break: false
disable-header-and-footer: false
header-left:
header-center:
header-right:
footer-left: "(C)Beru Hinode on behalf of Bedirhan KURT."
footer-center: "License: GPL-2.0-only"
footer-right:
subparagraph: true
lang: en-US 

math: katex
---

<!-- _backgroundColor: aquq -->

<!-- paginate: false -->

## Introduction to AOSP

### Week-1 (AOSP Introduction and History)

#### Android's Birth and Its Development Process

Download [DOC](week-1.en.md_doc.pdf), [SLIDE](week-1.en.md_slide.pdf), [PPTX](week-1.en.md_slide.pptx)

<iframe width=700, height=500 frameBorder=0 src="../week-1.en.md_slide.html"></iframe>

---

<!-- paginate: true -->

### Outline

- What is Android and what is it intended for
- AOSP's birth
- Custom ROMs and custom device development
- Android was originally made NOT by Google but an independent company

---

### What is Android?

When it comes to AOSP, which stands for Android Open Source Project, there are lots of people getting confused by the term even including majority of Android users themselves. So it's required to explain what is Android first.

---

Android is a mobile operating system developed by Google for various platforms such as smartphones, tablet PCs and even laptops. It not only kept itself up to date with today's world, but also is known to always have an open hole for development as per human requests constantly changing. Every few Android versions, Google comes with new design guidelines which are made to both look elegant and stay future-proof.

---

Nowadays, hundreds of thousands of people have been contributing to Android world by either their unique software based on it, contributing to upstream source code, manufacturing their own device with a modified version of it or simply porting it to plenty of devices you would never expect to see! We have even seen Android running on a Nintendo Switch!

---

### History of Android

Believe it or not, Android was originally intended to be made for digital cameras, developed by a now-acquired-by-Google Android Inc, an American tech company, started development in 2003. Before it could get its public release, it had lots of changes - It got acquired by Google, then rebased on the Linux kernel to be intended to be made for PCs as an OSS (Open Source Software) licensed under [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) in 2004.

---

In 2007, after 3 years since getting acquired and rebased by Google, Open Handset Alliance was found to make Android supported by even wider range of devices by providing the core features it now has such as installing 3rd party apps, wireless networking, etc.

---

In 2008, 1 year after foundation of O.H.A, T-Mobile got the chance to feature this brand new operating system with majority of Google apps built-in: Android 1.0, codenamed "Astro Boy". Throughout its development cycle, 4 minor releases (1.1~1.4) have been made in top of 1.0 without any codename changes.

---

In early 2009 was the first ever Android version we most probably know getting released, also making a huge change on Android's codenaming style that we know today: Android 1.5 "Cupcake". This release gave the UI some refreshments and lots of optimizations for touch screens as well as the introduction of on-screen keyboard that's the core feature that a smartphone and tablet PC has to offer today. It also introduced 3rd party widgets, which Apple surely still has a long way off for.

---

After semi-annual development cycle over Android Cupcake came Android Donut, incrementing minor release to 1.6 and getting released in Fall 2009. This release included adaptation to newer set of technologies such as over-the-air adaptation for different screen sizes and CDMA (also known as 3G network) support.

---

Keeping up the pace for development came the 2nd major version of Android, 2.0 "Eclair". This release is the first one to include, hold your horses because this is also something Android first introduced as well, speech-based navigation! As you would drive on road, the navigation would navigate you through towards your destination. It was also packed with introduction of live wallpaper support and speech-to-text, also known as speech dictation, availability. One downside though, it's also the first Android version to get a feature from iOS which made Apple extremely angry: Pinch to zoom. The next minor version, 2.1, didn't increment the codename but only was packed with some platform fixes.

---

Just after 4 months since 2.1 came 2.2, incrementing codename to "Froyo". This release included huge amounts of performance improvements as well as standardizing some features such as the well-known dock and speech commands. It wasn't like the Google Assistant we now have though. You could perform only simple tasks such as asking your phone to play some music or taking a note. It was unable to read your notifications or make a joke for you. This release was also packed with support for Shockwave Flash, which Apple resisted to provide in their iOS devices.

---

In 2010 came the next minor release that we all know well, Android 2.3 "Gingerbread". In the pure build without any modifications, it had the color green and black seeped all around the user interface. It was also the first Android version to introduce that three-tap easter egg which only had an art of Android and gingerbread in the middle of zombies. Tapping it would create a toast that reads "Zombie art by Jack Larson".

---

2011 was a really weird time for Android, introducing its tablet-focused redesigned user interface with the new design chief "Matias Duarte". Being the only completely proprietary major version of Android, 3.0 and 3.1 "Honeycomb", Motorola Xoom was the first model to debut it through. It introduced the first implementation of navigation dock that we would see lasting long and also debutted a prototype of Holo design, the combination of the colors blue and black as inspired by space-alike designs. It also introduced the card-like recents UI and the recents button. Previous Android versions would use icon-based "Task Manager" just like classic Windows Alt+Tab UI. Its easter egg was a bee with transparent background, posting the toast "REZZZZZZZ..." when you tap on it.

---

In a later date, again in 2011, comes Android 4.0 "Ice Cream Sandwich". This one made phones and tablets have a single unified UI with its more modern design approch. While it carried over the accent change, navigation dock (which would become navigation bar on phones), card-like recents UI and every other change Honeycomb did. It was pretty buggy and was known to have performance bottlenecks as all new major releases would have. Its easter egg was rather inspired by the well-known Nyan Cat, remaking it for Android and replacing the cat with the Android mascot made in pixelated style and with an ice cream sandwich cage. You would have to keep holding on your screen for it to appear as your phone vibrates stronger and stronger the more the Android grows. If you just tap, it would say "Android 4.0: Ice Cream Sandwich" in a toast.

---

The biggest impact to Android was made by 4.1 and 4.2 "Jelly Bean", packing lots and lots of improvements inside, released in 2012. It included lots of stability and performance includes over ICS, but also debutted the quick settings for the first time for mobile devices, and multi-user support for tablet PCs. It also packed in the support for widgets directly in lock screen as well as the Google Now feature. It also introduced interactive notifications such as additional functions like reply and mark as read, and expanded capabilities of voice commands. Its easter egg would show you a jellybean that would become the Android mascot's face when tapped on, along with a big custom toast saying "Android 4.1/4.2 **JELLY BEAN**". Long pressing on it would show you a screen with bunch of jellybeans floating around with which you could interact with and drag around.

---

2013 came the next minor release in Android 4.x family - 4.4 "KitKat". You guessed it right, this version's codename and easter egg was inspired by the Nestle KitKat, the chocolate! This release dropped the absolutely black backgrounds and absolutely blue accents. It also introduced support for transparent status bar and the first implementation of "OK Google" hotword, although it would work only when you're on home screen or in Google app with screen on. It also debutted its first ever Google Now page which was a feature exclusive to Nexus Launcher (now known as Pixel Launcher) users. Its easter egg would show you the letter "K" which would spin randomly as you tap on it, show the Nestle KitKat style "Android" text when you long press on it. Though, if you long press on it too, it would bring up the square style screen saver, showing icons for all Android versions ever released so far.

---

Fall 2014 was another breakthrough time for Android, debutting 5.0 codenamed "Lollipop" with its all-new design approach known as "Material Design". It has been substantially changed over the years but kept the base the same. The whole UI was redesigned, introducing "heads-up notifications" that would show important notifications and conversations on top of your screen for a short period of time as they come, notifications on lock screen to surpass requirements to unlock your device to see notifications, swipe-twice quick settings panel, support for LTE (A.K.A. 4G) and many many more. This is also the first release desktop-focused software based on Android would emerge. Though, it introduced lots of bugs along which would be ironed out the next year as well. Its easter egg would show a little circle which would change color and evolve into a lollipop as you tap, with the next "lollipop" taking place. Tapping on it for a few more times and then long pressing would bring up a Flappy Bird alike game designed around the Android mascot as the bird and lollipops as pipes as well!

---

Android 6.0 "Marshmallow" came along in 2015. Even though it seemed like a minor release, it had lots of things put over Android Lollipop: Now On Tap, a card-based Google Now interface you could access by long pressing on home button, new touch response, all-new Do Not Disturb, app-specific runtime permissions, support for fingerprint sensors, a bit more improved face unlocking in Smart Lock, support for USB-C, paginated QS, etc. It also introduced a hidden API for split screen, although buggy, support for "System UI Tuner" that allowed you to change several aspects of the UI. Its easter egg was around the same as Lollipop, except it directly shows the big circle with a special icon presenting the letter "M", which would then turn into Android-ified marshmallow and tapping a few more times then long pressing would bring the refreshed Android Flappy Bird that adds support for multiplayer same-screen gaming, allowing up to 6 users to participate on the same device.

---

Android 7.0 "Nougat" debutted in 2016 and has gotten even more significate features. Support for 3rd party tiles in quick settings and introduction of editing the QS, eventually dropping the separate Settings activity for editing those, is one of the most productive ones. It introduced inline reply function for notifications too, allowing you to reply notifications without the need to leave your current app. It also introduced a proper implementation of split screen that you could access by long pressing on recents button. It's also the first Android version to allow debutting of Google Pixel series, starting with Pixel and Pixel XL. It also introduced Google Assistant and the Data Saver feature. Along with those, although less known, it also introduced hamburger menu in Settings, allowing you to jump between Settings menus without the need to go back. Its easter egg would show you a card styled letter "N", which would bring up the famous QS-dependent cat game, also named "Neko" (猫, means "Cat" in Japanese) when tapped on multiple times then long pressed.

---

Android 8.0 "Oreo" launched in 2017, has tweaked the interface once again, introducing a wallpaper-dependent prototype of dark mode. It also introduced more productivity features such as Always On Display, notification snoozing, quick toggles for specific tiles such as WiFi and mobile data, Project Treble and so GSIs (Generic System Images) that eventually reduce the time OEMs would take to release newer updates, along with a hidden API for two-button navigation and so launcher-dependent recents activity in place of the one introduced in System UI. Google also introduced Android Go for low-end devices, the first implementation of Google Play Protect, the built-in antivirus for Android devices and redesigned emojis along with its event. Its easter egg on 8.0 would show three circles stacked inside each other, which then got replaced with the symbol of Oreo biscuit with Android emblem on top instead of "OREO" logo on 8.1. Tappping on it a few times then long pressing would open up another activity that shows a black octopus floating around in the depths of a blue sea, which you could move around by dragging its head.

---

The Android 8.0 commercial titled "Android Oreo - Open Wonder", featuring the traditions of the Oreo cookie too.

<iframe width="1164" height="655" src="https://www.youtube.com/embed/twZggnNbFqo" title="Android Oreo - Open Wonder" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

Android 9 "Pie" was launched in August 2018, eventually slowly redesigning the interface once again. The volume panel has been made more minimal and moved to sides of screen, depending on where your volume keys are. Android Pie also standardized swipe-up app drawer and made two-button navigation available, a more pleasant battery saver mode, which drops disablement of animations and filling of UI bars with the color orange, dropping expanded QS tiles and introducing Smart Reply. It also had a hidden API for full navigation gestures, although buggy, and is the last Android version to support recents dependent on System UI. Its easter egg would show the letter "P" in a stylish way with kind of hypnotizing animation, which in some devices would change color as you tap on it and launch a basic whiteboard activity that you could draw things on.

---

Android 10 "Q", the first Android version that didn't have a codename, was launched in September 2019. It brought a ton of new features such as the proper full screen navigation, updating runtime permissions so introducing scoped storage and hidden API for more tweakable location permission, making system-wide dark theme an actual thing and taking it out of being a prototype, a lot deeper system customization by using "Styles & Wallpapers", an all-new Focus Mode and on-demand live captions. It also dropped face unlock from Smart Lock, making it a device-specific implementation. Its easter egg would show the text "android 10", which you can turn into "android Q" then press a few times onto to bring an icon quiz to test how good you are with material design icons.

---

Android 11 "R", unofficially codenamed "Red Velvet Cake", was launched in September 2020, bringing the first ever proper implementation of home controls right in your power menu. It also brought the first implementation of music controls on quick settings, taking it out of notification panel and native screen recording. Its easter egg is a way more revamped version of Neko that was seen on Android Nougat, which can be triggered by rotating the white dot clockwise until the number "11" appears on screen. It got renamed to "Neko Controls" internally, although it's named "Cat Controls" as the app provider for home controls.

---

Android 12 "Snow Cone", launched in October 2021, revamped the interface for the 3rd time, bringing up a new wallpaper-based design guidelines named "Material You", As in its name, "it's meant to be for you", as in the system respecting the way you customize it. The interface got bigger elements that's aimed to be more accessible and consistent.  It also introduced smooth switch between regular screen on and AOD, eventually reducing unnecessary display power-offs for LCD displays. Its easter egg would show a clock that shows the current time, and rotating the minutes either clockwise or counterclockwise until it's 12:00 then releasing when it's 12:00, it would show the Android 12 icon with lots of differently sized circles resembling a color blindness test. This reveals 2 things at once: The home controls QS tile with Cat Controls being carried over from Android 11, and the Paint Chips widget showing the entire color palette generated from your wallpaper by Android 12's theming engine.

---

Android 13 "Tiramisu" was launched in the source code and released to first end-user device in August 2022. It introduced the revamped version of taskbar for tablet devices, and did some little minor tweaks throughout the System UI, just like the upgrade from Android Lollipop to Marshmallow. Its easter egg is about the same with Android 12's, with the only exception being that you have to make the clock show 1:00 instead of 12:00.

---

### What is AOSP?

AOSP, standing for Android Open Source Project, is Google's approach to make the Android operating system open source without blending in Google's proprietary aspects, eventually letting development for devices in multiple aspects whether if you're just an app developer, OEM or a custom platform developer. Its sources consist of lots of components but can be broken down to a few simple matters.

---

1. Build system, firstly coded in Make and Ninja then switched to Soong UI and Blueprint.

2. Framework, coded entirely in Java.

3. External components and utilities, adapted for Android and ARM processor.

4. Android packages, the apps that have direct connection with framework.

5. Device sources, combination of Makefiles and packages.

6. Linux kernel, made for a specific device.

7. Vendor proprietary blobs, straight up binaries and Makefiles specifying where to copy or install them.

--- 

### What if you want to contribute to it?

The source code is in [android Git repositories - Git at Google](https://android.googlesource.com) along with the Issue Tracker being located at [Google Issue Tracker](https://issuetracker.google.com/issues?q=Android%2F) (although bloated since a long time). You just do your change, then append `Test:` tag into your commit message, explaining how did you test the change, then submit to Google by uploading it to review by using `repo upload`.

---

### What is A "Custom ROM"?

ROM in computer terms means "Read-Only Memory". Based on this definition, we, custom software developers, define "ROM" as "software stored in read-only partitions". A custom ROM is a custom software Android devices store in their usually-read-only partitions such as `system`, `vendor`, `product`.

---

### List of Some Well-Known Custom ROMs

- [LineageOS](https://github.com/LineageOS) (Father of most of the Android projects)

- [Pixel Experience](https://github.com/PixelExperience) (Provides Pixel device functionalities to non-Pixel devices)

- [Evolution X](https://github.com/Evolution-X) (Similar to Pixel Experience, provides way deeper customization)

- [/e/OS](https://gitlab.e.foundation/e/OS) (LineageOS modified to be more privacy-aware)

- [GrapheneOS](https://github.com/GrapheneOS) (Pixel-first privacy-aware ROM)

- [ProtonAOSP](https://github.com/ProtonAOSP) (Pure AOSP with lots of platform fixes and little customization by a Pixel custom ROM developer)

- [Project Kaleidoscope](https://github.com/Project-Kaleidoscope) (Enterprise-degree ROM based on AOSP, partnering with OEMs to bring in a more professional system)

- [Libre Mobile OS Droid](https://git.libremobileos.com/LMODroid) (Professional-degree FOSS ROM based on LineageOS developed by a GSI maintainer, making various new features for Android completely opensource and easy to implement on other software)

---

## References

- Base for module: [github.com:ucoruh/course-note-sample](https://github.com/ucoruh/course-note-sample)
- History: [Android versions: A living history from 1.0 to 13 | ComputerWorld](https://www.computerworld.com/article/3235946/android-versions-a-living-history-from-1-0-to-today.html)
