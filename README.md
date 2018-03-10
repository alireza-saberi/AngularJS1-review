# AngularJS1-review
This is a personal review of AngularJS1.X to wrap up my thoughts, after these years of working while reading [rangleio blogs](https://ngcourse-1.rangle.io/).

Iy may take a long time to complete, but will helps me to get to stages every few weeks.

## Setup
- For Mac OS X, [iTerm2](http://iterm2.com/) is recommended. Believe me, it's awesome.
- Install [Angular Batarang](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk?hl=en), which is an Google Chrome extension that makes it easier to debug and inspect Angular applications
- [Postman](https://www.getpostman.com/) is the preferred tool for interacting with a REST API server.

## Intro
AngularJS 1.x does not have nearly the same kind of warts as JavaScript, but it does have features that will help you shoot yourself in the foot, even as many of its other features help you build highly scalable software.

```
The upcoming Angular 2 brings a number of changes. Some of those changes involve removing those parts of Angular that have proved
to not work well. Other changes involve borrowing the best ideas from outside the Angular ecosystem. Finally, another large set of
changes aims to take advantage of new features that are becoming available in ES6, the new version of JavaScript.
```

***AngularJS is often described as an MVC ("Model-View-Controller") framework (however, is far too simple!).***

However. "Controllers" are replaced with "View mMdels". Angular can be better understood as a "MVVM" ("Model-View-ViewModel") framework.

`Model = data`

`View = HTML part`

`ViewModel = $Scope/Controlers`


```
only the most trivial applications can be understood as consisting of a single model, a single view and a
single controller. More commonly, an application will include multiple views, multiple controllers, and multiple
data models. So, it might look more like this:
```
