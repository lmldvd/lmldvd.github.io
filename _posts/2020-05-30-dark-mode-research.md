---
title: Dark Mode Research
tags: [practice, coding]
style: border
color: warning
description: Doing some research!
---


## What is dark mode?

A bit of searching will have Wikipedia turn up eventually. There's a great wealth of information about the history of the color scheme. This is like the color combination that we see when reading on a E-Ink display, CRT monitors or when using a dark mode in our computer screens and mobile apps.

> Originally, computer user interfaces were formed on CRTs. The phosphor was normally a very dark color, and lit up brightly when the electron beam hit it, appearing to be green or amber on black, depending on phosphors applied on a monochrome screen. RGB screens continued along a similar vein, using all the beams set to "on" to form white.<br>_Quote from Wikipedia Page on the Light-on-Dark Color Scheme_

Dark mode reduces the brightness from device screens. They help reduce eye strain and facilitating screen use in dark environments – all while conserving battery power. I believe it also helps accessibility. Sometimes people find it harder to view a screen that has a full white background with not so dark letters. Design wise it is good to consider visiting a reference website such as [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) to make sure what you are publishing doesn't end up being an issue to others to read. 

![Dark Mode](https://i.imgur.com/b2TrB1I.png "Dark Mode in Google Material Design")
> A dark theme uses dark gray, rather than black, as the primary surface color for components. Dark gray surfaces can express a wider range of color, elevation, and depth, because it's easier to see shadows on gray (instead of black).
Dark gray surfaces also reduce eye strain, as light text on a dark gray surface has less contrast than light text on a black surface.<br>_Quote from Google's Mateial Design Dark Themes Page_

Personally I like dark mode toggles. Much as I like having choices when using anything really. I often go through options or settings to find ways to customize my viewing experience. It's also important to think about what other people experience. Having a strict layout may not be the best choice to publish, even if it looks pretty.

{% include elements/figure.html image="https://i.imgur.com/TC1k9xKm.png" caption="Dark Mode Buddy" %}

<br>


## Code to practice with

* Step 1: Add HTML

  _This includes_ `<body>` _or_ `<div>` :memo:

* Step 2: Add CSS

  _Gotta make it pretty_ :sparkles:

* Step 3: Add Javascript

  _Tinker with my favorite language_ :weary:
  
  <br>

### First up is the HTML & CSS:

>With the HTML set with `<body>` element created, style the `<body>` element and create a `.dark-mode` class for toggle.

```
body {
  padding: 25px;
  background-color: white;
  color: black;
  font-size: 25px;
}

.dark-mode {
  background-color: black;
  color: white;
}
```

<br>

### Then the JS:

>Get the <body> element and toggle between the .dark-mode class.

```
function myFunction() {
  var element = document.body;
  element.classList.toggle("dark-mode");
}
```

<br>

___
I traced the idea behind adding a dark/light toggle back to an interview about Windows Phones:
> _Dark backgrounds were added to Windows Phone 7 with energy consumption in mind since fully black pixels emit no light on OLED screens._
Neat.
___

<br>

### Reference

[How to from w3 Schools website](https://www.w3schools.com/howto/howto_js_toggle_dark_mode.asp) <br>
[Wikipedia article](https://en.wikipedia.org/wiki/Light-on-dark_color_scheme) <br>
[Material Design Guidance](https://www.material.io/design/color/dark-theme.html) <br>
[Mozilla Web Technologies for Developers](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme) <br>
[Section 508 or general guidance on accessibility](https://www.section508.gov/manage/laws-and-policies)
[Interview: Windows Phone 7 battery life, copy/paste, multitasking, and more](https://www.neowin.net/news/interview-windows-phone-7-battery-life-copypaste-multitasking-and-more)
