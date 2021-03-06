---
layout: page
title: "Browsers"
description: "Browser Compatibility List"
date: 2016-06-25 08:00
sidebar: true
comments: false
sharing: true
footer: true
---

Home Assistant requires a web browser to show the frontend. Not all browsers include features which are needed to use the Home Assistant frontend. If you are running into trouble, check the list below.

We don't test the web interface against all available browsers but this page tracks different browsers on various operating systems and should help you to pick a browser which works.

We would appreciate if you help to keep this page up-to-date and add feedback.

## {% linkable_title Microsoft Windows %}

| Browser                   | Release        | State      | Comments                 |
| :------------------------ |:---------------|:-----------|:-------------------------|
| Internet Explorer ([IE])  | 11             | partially | Streaming updates not working. Display issues |
| Microsoft [Edge]          | deli. Win 10   | partially | Streaming updates not working. |
| [Chrome]                  | 50.0.2661.102  | works      |                          |
| [Firefox]                 | 43.0.1         | works      |                          |
| [Iridium]                 | 48.2           | works      |                          |

## {% linkable_title MacOS %}

| Browser               | Release        | State      | Comments                 |
| :-------------------- |:---------------|:-----------|:-------------------------|
| [Safari]              |                | works      |                          |

## {% linkable_title Linux %}

| Browser               | Release        | State      | Comments                 |
| :-------------------- |:---------------|:-----------|:-------------------------|
| [Firefox]             | 47.0           | works      |                          |
| [Midori]              | 0.5.11         | works      |                          |
| [Chromium]            | 50.0.2661.102  | works      |                          |
| [Conkeror]            | 1.0.2          | works      |                          |
| [Konqueror]           |                | unknown    |                          |
| [Uzbl]                | 0.9.0          | works      |                          |
| [Opera]               |                | unknown    |                          |
| [Lynx]                | 2.12           | fails      | loads empty page         |
| [elinks]              |                | fails      | page with manifest and import |
| [w3m]                 | 0.5.3          | fails      | display the icon shown while loading HA |
| [Epiphany]            | 3.18.5         | works      |                          |
| [surf]                | 0.7            | works      |                          |

## {% linkable_title Android %}

| Browser               | Release        | State      | Comments                 |
| :-------------------- |:---------------|:-----------|:-------------------------|
| [Chrome]              | 50.0.2661.89   | works      |                          |
| [Firefox]             | 46.0.1         | works      |                          |

## {% linkable_title iOS %}

| Browser               | Release        | State      | Comments                 |
| :-------------------- |:---------------|:-----------|:-------------------------|
| [Safari]              |                | unknown    |                          |


[Firefox]: https://www.mozilla.org/en-US/firefox/
[Midori]: http://midori-browser.org/
[Chrome]: https://www.google.com/chrome/
[Iridium]: https://iridiumbrowser.de/
[Opera]: http://www.opera.com/
[Edge]: https://www.microsoft.com/en-us/windows/microsoft-edge
[IE]: http://windows.microsoft.com/en-us/internet-explorer/download-ie
[Safari]: http://www.apple.com/safari/
[Chromium]: https://www.chromium.org/
[Conkeror]: http://conkeror.org/
[Konqueror]: https://konqueror.org/
[Uzbl]: http://www.uzbl.org/
[Lynx]: http://lynx.browser.org/
[elinks]: http://elinks.or.cz/ 
[w3m]: http://w3m.sourceforge.net/
[Epiphany]: https://wiki.gnome.org/Apps/Web
[surf]: http://surf.suckless.org/
