
## firefox-ios - Class Project

Stage 0:

1. Project name: 
  - firefox-ios - firefox browser for ios
  - [firefox-ios Repository](https://github.com/mozilla/firefox-ios)
2. Team members:
    - [Rawi Sakhnini](https://github.com/rawisa)
    - [Marian Raad](https://github.com/marianera)
	


## Introduction

Firefox for iOS is a browser from Mozilla, for the Apple iPhone, iPad and iPod touch mobile devices.
It is the first Firefox branded browser to not use the Gecko layout engine as is used in Firefox for desktop and mobile. Due to Apple's application review policies, Firefox uses the built-in iOS WebKit-based rendering framework instead of Gecko.
Firefox for iOS supports Firefox Sync and is able to sync Firefox's browsing history, bookmarks, and recent tabs.

## Architecture

**A general browser architecture:**

![](general.jpg)
**[REF]{http://image.slidesharecdn.com/web-browserarchitecture-150609231155-lva1-app6892/95/web-browser-architecture-2-638.jpg?cb=1433891674)**


**Firefox** architecture looks as the following figure, but because of Apple policies they had to use the build-in ios WebKit instead of gecko.

![](firefox-diagram.jpg)
**[REF](http://www.shinylight.com/wp-content/uploads/2009/09/11.jpg)**


## Resources 

Firefox is an open-source browser, users around the world help to improve it.
Contributers can communicate through: 
* IRC:            [#mobile](https://wiki.mozilla.org/IRC) for general discussion and [#mobistatus](https://wiki.mozilla.org/IRC) for team status updates.
* Mailing list:   [mobile-firefox-dev@mozilla.org](https://mail.mozilla.org/listinfo/mobile-firefox-dev).

They can find the bugs that need to be fixed at the following list:

* Bugs:           [File a new bug](https://bugzilla.mozilla.org/enter_bug.cgi?bug_file_loc=http%3A%2F%2F&bug_ignored=0&op_sys=iOS%20&product=Firefox%20for%20iOS&rep_platform=All) • [Existing bugs](https://bugzilla.mozilla.org/describecomponents.cgi?product=Firefox%20for%20iOS) 



# Statics


**The weekly commits:**
![](commit-cont.png)
**[REF](https://github.com/mozilla/firefox-ios/graphs/commit-activity)**


**Notice the high code change frequency:**
![](code-freq-statics.png)
**[REF](https://github.com/mozilla/firefox-ios/graphs/code-frequency)**


Looking at the following release frequency, one can understand that firefox uses the agile method.
Also according to [itbusinessedge](http://www.itbusinessedge.com/cm/blogs/all/mozilla-takes-hybrid-approach-to-agile-software-development/?cs=38988):
"Mozilla has also begun using a hybrid model that incorporates elements of both agile and waterfall approaches for its flagship Firefox Web browser. The goal is to more quickly introduce new features -- aided by agile's emphasis on iterative releases -- while maintaining backward compatibility, security and overall code quality.".
![](release-statics.png)
**[REF](https://github.com/mozilla/firefox-ios/releases)**



Firefox has bugs/features list in their [issues](https://github.com/mozilla/firefox-ios/issues) in github:
![](issues.png)
**[REF](https://github.com/mozilla/firefox-ios/issues)**

## Contributor guidelines

Using Firefox official site [Bugzilla](https://bugzilla.mozilla.org/). Developers can find a list of bugs in firefox
All developers must follow the following Swift style to keep the code orginized: https://github.com/raywenderlich/swift-style-guide.
With small * Exception: we use 4-space indentation instead of 2.

Further info can be find on [firefox-ios Repository](https://github.com/mozilla/firefox-ios#contributor-guidelines)