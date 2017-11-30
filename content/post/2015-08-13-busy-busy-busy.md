---
author: shidima
categories:
- Uncategorized
date: 2015-08-13T21:48:26Z
guid: http://drunkturtle.com/?p=9
id: 9
title: Busy, busy, busy
url: /2015/08/13/busy-busy-busy/
---

Time fly's when your having fun! Its been over 2 months since I made a post, not really what I was planning on. It's not like I'm having writers block, I just haven't found the time to write. Between work and the house and me being lazy I'm just to busy =)
<h2>The current programming language</h2>
<em>Drum roll...</em> is JavaScript! As posted before, I'm trying to make an App for my wife. I tried Java and Android or C# and Xamarin, but Javascript with <a href="https://cordova.apache.org" target="_blank">Cordova</a> / <a href="http://phonegap.com/" target="_blank">PhoneGap</a> Or <a href="http://ionicframework.com" target="_blank">Ionic</a> / <a href="http://www.appgyver.com/steroids" target="_blank">steroids.js</a> seems to be a lot simpler. Taking a photo and getting it to actually show is only a few lines of code, and you don't have to work with intents or promises.

The same goes for saving data. I'm using local storage now to save data by stringify'ing a JSON object with the <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify" target="_blank">JSON.stringify</a> function. This works great, as all I need to save is text data. If you need more complex things to store, you maybe better of with a SQLite solution.