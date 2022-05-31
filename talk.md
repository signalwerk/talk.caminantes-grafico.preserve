---
tags: TeamTalk
slideOptions:
  theme: white
  controls: false
---

{%hackmd Da4CJ3vgR9yHy7H06U5byQ %}

<style>
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap');
    
    :root {
        --r-heading-text-transform: none;
        --r-main-font: 'Open Sans';
        --r-heading-font: 'Open Sans';
        --r-heading-font-weight: 700;
        --r-heading-color: #0054a2;
        --r-link-color: #006984;
        --r-heading-margin: 0 0 .6em 0;
    }
    
    :root .reveal {
        font-family: var(--r-main-font);
    }
    
    
    :root .reveal img {
        max-height: 65vh;
        max-width: 50vw;
    }
    
    
.scroll {
  height: 0;
  overflow: hidden;
  padding-top: calc(9 / 16 * 100%);
  background: white;
  position: relative;
}
.scroll__inner {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  overflow-y: auto;
}
    
    :root .reveal .scroll img {
        max-height: none !important;
    }    
</style>



# Preserve a website for <br>the next 10 years
**longevity of web-technology**

<br />
<br />
<br />

<small>2022 · Stefan Huber</small>

---

## Disclaimer

* This talk is only an «experiment»!
* Don't do it this way if you don't have to!
* see [caminantes-grafico.org](https://caminantes-grafico.org/)

---

## Background

* 2011 · «walz» with friend
* 3 months for food and shelter in the USA
* Project Page to get contacts/jobs
* [Gringografico](http://gringografico.com/) was first


---

## Project Page

→ let's have a look

---

## The Problem

![](https://i.imgur.com/oDe6ESv.png)

---

## 2011 · Typo3 installation 

![](https://i.imgur.com/G1BzUkX.png)


---

## What breaks first?

* PHP (Application Server)
* Database
* Image processing (IM)
* Proprietary formats
* External resources


---

## What doesn't break

* Static Webhosting
* Web Standards
* Keep the data open
* Keep the processing simple


---

## Let's rebuild it static

---

## Keyparts

* Map
* Content


---

## React Simple Map

* [react-simple-maps](https://www.react-simple-maps.io/)
* Richard Zimerman · z creative labs 


---

## React Simple Map

![](https://i.imgur.com/kTNdOmW.png)


---

## Content

* SQL-Dump not helpfull
* Let's parse the HTML

---

## Example


![](https://i.imgur.com/INLZwse.png)


---

## HTML

<div class="scroll">
<div class="scroll__inner">

```html

	<!--  CONTENT ELEMENT, uid:499/text [begin] -->
		<div id="c499" class="StandardContentItem" >
		<!--  Text: [begin] -->
			<p>___.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.__&nbsp;&nbsp;&nbsp;<br /> \_&nbsp;|__&nbsp;_____&nbsp;&nbsp;&nbsp;&nbsp;______&nbsp;____&nbsp;|&nbsp;&nbsp;|&nbsp;&nbsp;<br /> &nbsp;|&nbsp;__&nbsp;\\__&nbsp;&nbsp;\&nbsp;&nbsp;/&nbsp;&nbsp;___//&nbsp;__&nbsp;\|&nbsp;&nbsp;|&nbsp;&nbsp;<br /> &nbsp;|&nbsp;\_\&nbsp;\/&nbsp;__&nbsp;\_\___&nbsp;\\&nbsp;&nbsp;___/|&nbsp;&nbsp;|__<br /> &nbsp;|___&nbsp;&nbsp;(____&nbsp;&nbsp;/____&nbsp;&nbsp;&gt;\___&nbsp;&nbsp;&gt;____/<br /> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> </p>
		<!--  Text: [end] -->
			</div>
	<!--  CONTENT ELEMENT, uid:499/text [end] -->
		
	<!--  CONTENT ELEMENT, uid:498/text [begin] -->
		<div id="c498" class="StandardContentItem" >
		<!--  Text: [begin] -->
			<p>-------------------------------------------------------------------------
</p>
<p>2011-09-26 | hyperwerk
</p>
<p>-------------------------------------------------------------------------</p>
		<!--  Text: [end] -->
			</div>
	<!--  CONTENT ELEMENT, uid:498/text [end] -->
		
	<!--  CONTENT ELEMENT, uid:497/textpic [begin] -->
		<div id="c497" class="StandardContentItem" >
		<!--  Image block: [begin] -->
			<div class="csc-textpic csc-textpic-left csc-textpic-above"><div class="csc-textpic-imagewrap"><ul><li class="csc-textpic-image csc-textpic-firstcol" style="width:300px;"><img src="t3/typo3temp/pics/94b08a133a.jpg" width="300" height="225" alt="" /></li><li class="csc-textpic-image csc-textpic-lastcol" style="width:300px;"><img src="t3/typo3temp/pics/f358bc94b0.jpg" width="300" height="226" alt="" /></li></ul></div><div class="csc-textpic-text"></div></div><div class="csc-textpic-clear"><!-- --></div>
		<!--  Image block: [end] -->
			</div>
	<!--  CONTENT ELEMENT, uid:497/textpic [end] -->
		
	<!--  CONTENT ELEMENT, uid:500/text [begin] -->
		<div id="c500" class="StandardContentItem" >
		<!--  Text: [begin] -->
			<p>&nbsp;</p>
<p>Quite a while ago we got an invitation from <a href="http://hyperwerk.ch/" title="Opens external link in new window" target="_blank" class="external-link-new-window" >[hyperwerk]</a> in Basel (Switzerland) to give a speech about going abroad. All right� We were away, we had a request and we had definitely no idea how to fill four (!) lessons with rich content. However, we did not start with preparing for the speech� Instead we decided, we have to bribe the students with a personal gift. So we started to order cardboard, did screenprint, bought a corner rounder and invested a shitload of work to produce an edition of sixty fans. But in the end we couldn�t sneak around the preparations for the day itself. 
</p>
<p>Apart of a loose of orientation in Basel we had an awesome time. The school is situated in the heart of the inner city and its building is astonishing beautiful. For the first time we saw in real, what we knew since years from the webpage � the hyperwerk! What a great concept for a school. The responsibility to set a focus of the study is delegated to the students themselves. They can choose between many teachers, workshops and topics. And we were part of it! If you also like to see what we did, you can download the <a href="http://www.caminantes-grafico.org/dl/2011_hyperwerk_big.pdf" title="Initiates file download" target="_blank" class="download" >[presentation | pdf 151MB]</a> or the same with <a href="http://www.caminantes-grafico.org/dl/2011_hyperwerk_slim.pdf" title="Initiates file download" target="_blank" class="download" >[less pictures | pdf 60MB].</a>
</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
		<!--  Text: [end] -->
			</div>
	<!--  CONTENT ELEMENT, uid:500/text [end] -->
		
	<!--  CONTENT ELEMENT, uid:457/text [begin] -->
		<div id="c457" class="StandardContentItem" >
		<!--  Text: [begin] -->
			<p>&nbsp;&nbsp;_________&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_____&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;__&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.__&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> &nbsp;/&nbsp;&nbsp;&nbsp;_____/____&nbsp;&nbsp;&nbsp;&nbsp;____&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;_&nbsp;&nbsp;\&nbsp;&nbsp;&nbsp;_____/&nbsp;&nbsp;|_&nbsp;&nbsp;____&nbsp;&nbsp;&nbsp;____&nbsp;|__|&nbsp;____&nbsp;&nbsp;<br /> &nbsp;\_____&nbsp;&nbsp;\\__&nbsp;&nbsp;\&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;&nbsp;\&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;/_\&nbsp;&nbsp;\&nbsp;/&nbsp;&nbsp;&nbsp;&nbsp;\&nbsp;&nbsp;&nbsp;__\/&nbsp;&nbsp;_&nbsp;\&nbsp;/&nbsp;&nbsp;&nbsp;&nbsp;\|&nbsp;&nbsp;|/&nbsp;&nbsp;_&nbsp;\&nbsp;<br /> &nbsp;/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\/&nbsp;__&nbsp;\|&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;\&nbsp;/&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;\&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;\&nbsp;&nbsp;|&nbsp;(&nbsp;&nbsp;&lt;_&gt;&nbsp;)&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;\&nbsp;&nbsp;(&nbsp;&nbsp;&lt;_&gt;&nbsp;)<br /> /_______&nbsp;&nbsp;(____&nbsp;&nbsp;/___|&nbsp;&nbsp;/&nbsp;\____|__&nbsp;&nbsp;/___|&nbsp;&nbsp;/__|&nbsp;&nbsp;\____/|___|&nbsp;&nbsp;/__|\____/&nbsp;<br /> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br /></p>
		<!--  Text: [end] -->
			</div>
	<!--  CONTENT ELEMENT, uid:457/text [end] -->
		
```

</div>
</div>

---

## Parser

* Processing of the HTML with `cheerio`
* Convert structure
* Text to Markdown
* Fix URLs (`http://` vs. `https://`)


---

## Data as JSON


<div class="scroll">
<div class="scroll__inner">

```json
[
  {
    "type": "post",
    "city": {
      "title": "Basel",
      "longitude": 7.5878261,
      "latitude": 47.5581077,
      "slug": "basel"
    },
    "title": "hyperwerk",
    "date": {
      "from": "2011-09-26"
    },
    "author": "both",
    "content": [
      {
        "type": "grid",
        "cols": [
          {
            "type": "col",
            "content": [
              {
                "type": "img",
                "src": "/img/blog/94b08a133a.jpg"
              }
            ]
          },
          {
            "type": "col",
            "content": [
              {
                "type": "img",
                "src": "/img/blog/f358bc94b0.jpg"
              }
            ]
          }
        ]
      },
      {
        "type": "text",
        "markdown": "Quite a while ago we got an invitation from [\\[hyperwerk\\]](https://hyperwerk.ch/) in Basel (Switzerland) to give a speech about going abroad. All right… We were away, we had a request and we had definitely no idea how to fill four (!) lessons with rich content. However, we did not start with preparing for the speech… Instead we decided, we have to bribe the students with a personal gift. So we started to order cardboard, did screenprint, bought a corner rounder and invested a shitload of work to produce an edition of sixty fans. But in the end we couldn’t sneak around the preparations for the day itself.  \nApart of a loose of orientation in Basel we had an awesome time. The school is situated in the heart of the inner city and its building is astonishing beautiful. For the first time we saw in real, what we knew since years from the webpage – the hyperwerk! What a great concept for a school. The responsibility to set a focus of the study is delegated to the students themselves. They can choose between many teachers, workshops and topics. And we were part of it! If you also like to see what we did, you can download the [\\[presentation | pdf 151MB\\]](/assets/dl/2011_hyperwerk_big.pdf.zip) or the same with [\\[less pictures | pdf 60MB\\].](/assets/dl/2011_hyperwerk_slim.pdf)"
      }
    ]
  },
]
```

</div>
</div>

---

## Modernize


---

## Structure

```html
<!DOCTYPE html>
<html lang="en" class="root">
  <head>
    <title>Home</title>
    …
  </head>
  <body>
    <div class="layout">
      <div id="layout__map"></div>
      <div id="layout__content">
        …navigation…
        …content…
      </div>
    </div>
  </body>
</html>
```

---

## Structure

```html
<!DOCTYPE html>
<html lang="en" class="root">
  <head>
    <title>Home</title>
    …
  </head>
  <body>
    <div class="layout">
      <div id="layout__map"></div> ← STATE
      <div id="layout__content">
        …navigation…
        …content…
      </div>
    </div>
  </body>
</html>
```



---

## Rendering

* `en/blog/index.html` HTML
* `en/blog/index.json` JSON





---

## Home

```html
<!DOCTYPE html>
<html lang="en" class="root">
  <head>
    <title>Home</title>
    …
  </head>
  <body>
    <div class="layout">
      <div id="layout__map"></div>
      <div id="layout__content">
        …navigation…
        <a href="/en/blog/">Blog</a>
        …content…
      </div>
    </div>
  </body>
</html>
```

---

## Data 

fetch `en/blog/index.json`

```json
{
    title: "Blog",
    lang: "en",
    className: "content-page",
    children: "<div>…html…</div>"
}
```

---


## Blog

```html
<!DOCTYPE html>
<html lang="en" class="content-page"> ← SET lang, class
  <head>
    <title>Blog</title> ← SET title
    …
  </head>
  <body>
    <div class="layout">
      <div id="layout__map"></div>
      <div id="layout__content"> ← SET children
        …new navigation…
        …new content…
      </div>
    </div>
  </body>
</html>
```

---

## Hijack links

```js
link.addEventListener("click", (e) => {
    e.preventDefault();
    const data = await (await fetch(
        `${link.getAttribute("href")}/index.json`)
    ).json();
    document.getElementById("layout__content").innerHTML = data.children;
    document.documentElement.setAttribute("lang", data.lang);
    document.documentElement.className = className;
    document.title = title;
});
```

---

## How to render the HTML/JSON?

---

## Static Rendering


```js
import html from "escape-html-template-tag";
import { Navigation } from "../Navigation/index.js";
import { Content } from "../Content/index.js";

function Layout({ children, path }) {
  return html`<div class="layout">
    <div id="layout__map"></div>
    <div id="layout__content">
      <div class="layout__navigation">
        ${ Navigation(path) }
      </div>
      <div id="layout__main">
        ${ Content({ children }) }
      </div>
    </div>
  </div>`;
```

---

## Webfont


![](https://i.imgur.com/KafGMxm.png)


---

## Webfont


![](https://i.imgur.com/KiEINVy.png)

---

## Rebuild Map


![](https://i.imgur.com/IPG3zUE.png)

---


## URL handling


![](https://i.imgur.com/iHNVJbD.png)


---

## Loading...

![](https://i.imgur.com/MqOfMFM.png)



---

## Loading...

![](https://i.imgur.com/Up8kQq6.png)


---

## And more

* Convert Flash-Videos with `ffmpeg`
* All Pixel-Icons to Vectors


---

## well…

* No «retina» pictures (Device Pixel Ratio)
* No text corrections…
* Mobile design…


---

## It goes on



* [2018 · Alexander Bönninger](https://walz.alexanderboenninger.de/)


---

## exit 0; thx

Questions?

