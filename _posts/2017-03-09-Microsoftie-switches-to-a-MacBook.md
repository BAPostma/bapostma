---
title: "Microsoftie switches to a MacBook"
tags: apple mac osx windows
---

## Some background
As a software engineer that has worked almost exclusively with Microsoft technology (C#, .NET, Windows Server) and with occasional exposure to Linux environments - I've never refrained from critisizing products that were not in my day-to-day workspace.

Many around me have had their moment of joy when I told them that I was given a MacBook Pro in my new job, and that we're using Google G-Suite instead of Office and Exchange. The latter I'll leave for a future post (as Google probably [already knows](https://www.theguardian.com/technology/2014/apr/15/gmail-scans-all-emails-new-google-terms-clarify)).

Upon joining [ThoughtWorks](https://www.thoughtworks.com) in my new job as a software consultant, it was unavoidable to be given a company laptop - one of the many virtues available to few not too long ago.

To be exact, we were handed crispy new MacBook Pro devices - yes, 'the one with the touch bar?' a fan would ask. Yes, 'the one without a hard-escape key and function keys?' a developer would ask.

__In this post I'll try to share my findings and honest opinion, being a Windows power user who switched to macOS Sierra.__ Forgive some of the links though, they'll be intentional sarcasm. :-)

## Impressions
### Unboxing
Apple has set a high bar for the experience and design, as we all know with their 'Designed in California' and [other catchphrases](https://qz.com/777628/the-slogan-for-apples-aapl-new-iphone-7-translates-into-this-is-penis-in-hong-kong/). I can't help to admit thinking "let's see about that".

The box looks nice and feels sturdy, but one wonders why you can't get the *apple out of the box* without flipping the whole box over. Was it such a design problem to add a little hole where you can get your finger underneath the device?
The [charge-only USB-C cable](http://www.apple.com/shop/question/answers/product/MLL82AM/A/is-this-a-thunderbolt-3-cable-or-just-a-usbc-cable/QT4CFYH92TCAK2242) is nicely rolled up like a snake and placed under the device. Putting that back after unrolling it, is an almost impossible job. As there's no other space or cavity in the box, you're going to have to carry that around.

The keyboard is nice. It has a gentle click on start and end of a travel, but the return key could be horizontally aligned with shift, to reduce finger stretching. The keyboard backlighting looks smooth, but there was not budget left to give the Caps-lock key a stylish colour when turned on.

### Starting up
The [OOBE](https://en.wikipedia.org/wiki/Out-of-box_experience) is nice. There was no [tasteful](https://soundcloud.com/yungterra/startupdmg) start-up sound and the first touch on the touchpad is soft and smooth the way only MacBooks have achieved. After setting up my account I expect to click on my profile picture to enter the password. Wrong. Apple's design talent has decided that you need to explicitly click on your name underneath, in order to show the password box. When a first attempt at my password failed as I only typed on this new keyboard for the first time, I was already annoyed by the 'no-shaking' input box. Tastes differ, especially in design, but I felt childishly patronised by this form of [skeuomorphism](https://www.interaction-design.org/literature/article/skeuomorphism-is-dead-long-live-skeuomorphism).

### Mac Explor... eh, Finder
Power user or not, Windows users are wired to do their Ctrl+X for cutting, Ctrl+C for copying and Ctrl+V for pasting. Following the basic rule that the Command ⌘-key usually replaces the Ctrl key, I was surprised that cutting and pasting files resulted in duplicates. Apparently, when pasting with the intention to *move* a file, the user must press the Option ⌥-key whilst command-v'ing. To make it even [less confusing to the user](https://discussions.apple.com/message/13302621?messageID=13302621), there is a Cut option in Finder's edit-menu which is unavailable!

The inconsistency of having to copy a file with the intent of moving it when pasting, is logically incorrect.

In search of other properly designed, very basic user features, I studied the context menu that opens when two-finger-tapping (maclish for right-clicking) and was surprised by its _structural_ and _linguistic_ inconsistency. One of the first options is to 'Move to trash' - long wording for 'remove' or 'delete'. Then after some separator 'get info' is listed, which equates to Windows' File Properties dialog box. What follows is a handy 'duplicate' option with lesser used functions below it to eventually arrive at 'Copy [filename]'. Can anyone explain why the filename (or x items when multiple items are selected) is displayed here when that's not the case for 'open', 'get info' or 'rename'? Lastly, the 'Quick look' feature (also invoked by the space-bar) is a very fast way to preview files such as images, videos and PDFs, but unfortunately not supported by a lot of other formats.

Connecting to a remote fileshare is easy and works very fast over SMB. When you're a power user with hidden files visible in Windows, expect to see [.DS_Store files all over the place](https://www.aorensoftware.com/blog/2011/12/24/death-to-ds_store/) on your [network](https://support.apple.com/en-gb/HT1629) and USB drives.

### The Dock & desktops
The Command+space bar opens spotlight to quickly run a program. I like this as the Start Menu becomes tedious as it grows with programs. Without it however, you can resort to the launchpad (which is on the touch bar) or your dock-bar at the bottom of the screen. Or... open a finder window, navigate to applications and selecting the right application from there. (Don't hit return though, that will rename a file instead of opening it!?)

Maximizing a window only seems possible when you want to put it into full-screen mode. Again, the Option key provides some relief, though it doesn't work all the time. Closing a window is easy, but remember that unlinke mobile devices, applications don't close themselves. After you've closed the main window, the application itself may still be running - you can see this by the little '.' under the icon in the Dock. Close that by Cmd+Q. Double work with little benefit on modern computers: application start-up time is fast enough usually.

Lastly, on the right hand side of that Dock, there is [some separator](https://www.lifewire.com/add-custom-and-standard-doc-spacers-to-mac-2260861) that I don't understand the use of. Some documents that are opened in an application show on the right, some don't at all. I suspect it is up to app developers to make us of, which they havent?

### Multiple windows
Windows logo key+tab, is the unmatched key combination that enables fast-window switching. It's mac-ternative Command+tab is a sheer productivity disappointment: it only allows switching between applications, [not their windows](http://apple.stackexchange.com/questions/2718/best-app-to-switch-between-all-open-windows). Within applications you're left with hoping they've implemented a Ctrl+tab feature, which may switch between tabs, like Chrome does. Those tabs by the way, can be opened in a Finder window too, something Windows [should've added years ago](http://ejie.me/).

When working with multiple windows in the full-screen mode, the multiple-desktop experience is incredibly efficient. You can switch quickly and very smoothly between the different screens using a three-finger-swipe to the left or right. An overview of the windows is beautifully displayed with a three-finger-swipe up.

If you're a keyboard person like myself, avoiding the mouse or touchpad has proven difficult. Navigating the multiple windows can be done by pressing Ctrl+arrow up, but using arrow keys from there doesn't work. This is a missed opportunity that should be easy to resolve in an update.

## Touch-bar
It is a nice idea, but that's all. The touch bar hasn't really proven itself to be useful for me yet, apart from the volume controls and lock-key. Nevertheless, the tendency to touch the screen when browsing the web makes the touch bar feel like a cheap alternative to building a fully touch capable device. Whilst coding, I miss the hard-escape key - despite it being displayed the majority of the time. I'll leave it at, I don't understand the [hype](http://www.stuff.tv/features/macbook-pros-touch-bar-worth-hype) around it.

## External devices
With my doubts about the ergonomics of Apple's mice and keyboards I ordered a bluetooth mouse. Yes, a Microsoft one. Not because of the name, because I'm a fan of their economic design and their [Bluetrack technology](http://mousearea.com/what-is-bluetrack-technology/).

A basic issue is the scrolling: you cannot specify the touchpad to use natural-scrolling and use 'regular' scrolling for an external mouse. Effectively I have to get used to scrolling up to go down, on my mouse now. A large miss where Apple could've cared a bit more about other hardware. 

As the mouse is connected via Bluetooth (no regular USB ports anymore) I'm constantly faced with messages on the screen 'mouse disconnected' and 'mouse connected' when the bluetooth connection goes to sleep.

What with the missing headphone jack on the new iPhone, I'm very happy that the USB-C ports have not taken the place of a mini-jack, allowing me to plug in a normal headphone set.

# Ending positively - conclusion
This post has mainly been a braindump of some first observations. My experience with VMWare Fusion, Chrome (which is nice and consistent across platforms), VS Code and the Terminal has so far made me quite productive and I'm very satisfied with the battery life that lasts almost a working day. The latter can potentially be longer, if I were to close my 50+ Chrome tabs, a Virtual Machine and various Docker containers.

I have no doubt I can be productive and grow to like my new workflow. But, as with your mum's pancakes, nowhere is as nice as it is at home. Home is what Windows still is for me.