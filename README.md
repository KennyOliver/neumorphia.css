# neumorphia.css :art: :package:
<img src="https://user-images.githubusercontent.com/70860732/110527002-604b3980-810e-11eb-9d83-3501443f07b8.jpeg" align="right" width="50%" >

![CodeFactor](https://www.codefactor.io/repository/github/KennyOliver/neumorphia.css/badge?style=for-the-badge)
![Latest SemVer](https://img.shields.io/github/v/tag/KennyOliver/neumorphia.css?label=version&sort=semver&style=for-the-badge)
![Repo Size](https://img.shields.io/github/repo-size/KennyOliver/neumorphia.css?style=for-the-badge)
![Total Lines](https://img.shields.io/tokei/lines/github/KennyOliver/neumorphia.css?style=for-the-badge)

<!-- [![repl](https://repl.it/badge/github/KennyOliver/neumorphia.css)](https://repl.it/@KennyOliver/neumorphia.css) -->

**Make websites elements modern & beautiful with neumorphia.css!**

Compatible with FontAwesome!

<!-- Note: repl.it projects that have a "." in the name, have it removed -->
[![Website Link](https://img.shields.io/badge/See%20A%20Demo-252525?style=for-the-badge&logo=safari&logoColor=white&link=https://kennyoliver.github.io/neumorphia.css/)](https://kennyoliver.github.io/neumorphia.css/)
[![neumorphia.css](https://img.shields.io/badge/Get%20neumorphia.css-75D2AF?style=for-the-badge&logo=css3&logoColor=252525&link=https://kennyoliver.github.io/neumorphia.css/neumorphia.css)](https://kennyoliver.github.io/neumorphia.css/neumorphia.css)

## :package: Installation & Update:
Use this code in the header of your HTML file - neumorphia.css will be automatically updated without your intervention!
```html
<link rel="stylesheet" href="https://kennyoliver.github.io/neumorphia.css/neumorphia.css">
```

**Upcoming feature:** Older versions will begin to be saved within folders; so that you can use version numbers in your URL, for ease of use.

---

## :art: How to use neumorphia.css
This section will go over how to incorporate elements of neumorphia.css in your HTML file.
Make sure to refer back to this when you first begin using neumorphia.css; these instructions may change!

### :warning: Quick Heads-Up!
* **A light background (e.g. white) is not compatible!**
* Elements are made from **divs**, apart from "hr-bar"
* **"hr-bar"** is an **exception** to the guidelines for neumorphia.css
* Instructions will be provided of how to structure your HTML code using containers provided by neumorphia.css

### Structuring your code
neumorphia.css works best when you use containers.
There a 2 provided: "chunk" and "group".

#### "chunk"
Use "chunk" as a container for encapsulating a section of HTML that uses neumorphia.css
"chunk" creates a row.
"chunk" isn't an element, and therefore does not need the main "neu" class.
```html
<div class="chunk"><div>
```

#### "group"
Use "group" as a container for encapsulating groups of neumorphia.css elements.
"group" will automatically position itself when you have many "group"s in the same "chunk"
```html
<div class="chunk">
  <div class="group"></div>
  <div class="group"></div>
</div>
```

"group" can also be used within neumorphia.css elements to help structure their contents or their children elements.

### Elements

#### Styling your elements
**Give all elements the main "neu" class.**
```html
<div class="neu ..."></div>
```

#### "hr-bar"
* "hr-bar" is the only exception of elements; but it's very simple to use
* Use ```html <hr "hr-bar"> ```
* Place it wherever: between "chunk"s, "group"s, elements, etc.

#### "squircle" & "circle"


---
Kenny Oliver ©2021
