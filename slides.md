
## Drupal 10 and beyond

---

### About me

@larowlan

<img src="./images/avatar2.jpg" alt="avatar" class="img--offscreen fragment fade-out" />
<img src="./images/avatar3.jpg" alt="avatar" class="img--offscreen fragment fade-in-then-out" />
<img src="./images/avatar4.jpg" alt="avatar" class="img--offscreen fragment" />

Note:

- Drupal development for 13 years
- PHP Development for 20
- Core committer, Security team you're probably using one of my modules

---

### ️Overview

<ul>
<li class="fragment fade-in-then-semi-out">Where are we?</li>
<li class="fragment fade-in-then-semi-out">Where are we going?</li>
<li class="fragment fade-in">Where do we need to go?</li>
</ul>

Note:

- One of my typical navel gazing exercises

---

### Chapter 1: Where are we?

---

### Drupal 10 will come out next year

---

### Three scenarios

<ul>
<li class="fragment fade-in-then-semi-out"><strong>Planned: June 15 2022</strong></li>
<li class="fragment fade-in-then-semi-out">Fallback: August 17 2022</li>
<li class="fragment fade-in">Break-glass: December 14 2022</li>
</ul>

---

### Drupal 9

Drupal 9.3 is due December 8
<p class="small fragment fade-in">*Please help us test the pre-releases</p>

---

### Drupal 9.4

<ul>
<li class="fragment fade-in-then-semi-out">Drupal 9.4 will co-incide with Drupal 10.0*</li>
<li class="fragment fade-in">Drupal 10.0 with deprecated code</li>
</ul>

<p class="small fragment fade-in">*All things going to plan</p>

---

### Drupal 8

<img src="./images/drupal8.jpg" alt="drupal 8" class="fragment fade-in"/>

Note: 

- Drupal 8 came out in 2015 and is nearly 6 years old
- iphone 6
- star wars episode 8 was in cinemas

---

<!-- .slide: data-transition="fade" -->

### 🪦 Drupal 8 is EOL

---

<!-- .slide: data-transition="fade" -->

### 🪦 Drupal 8 is End Of Life

---

<!-- .slide: data-transition="fade" -->

### 🪦 Drupal 8 will have no more security updates*

<p class="small fragment fade-in">*All things going to plan</p>

Note:

- So if you're still on Drupal 8, your job next week is to move to Drupal 9

---

### 🧚 Updating to Drupal 9 is much easier

https://pnx.me/3C6v3kH

Note:

- Provided you're on Drupal 8

---

### But I'm on Drupal 7!

<img src="./images/drupal7.jpg" alt="drupal 7" class="fragment fade-in"/>

Note:

- Drupal 7 came out in 2011
- You were rocking an iphone 4
- thunderbolt displays just came out
- Game of Thrones season 1 was just out
- 2 years before Brooklyn 99
- the last harry potter movie was in cinemas

---

### Drupal 7 is older than Doge

<img src="./images/doge.jpg" alt="doge" />

Note:

- Drupal 7 is the Windows XP of Drupal
- And I don't mean that its the only thing your grandparents and banks can agree on

---

### Drupal 7

<ul>
<li>Is end of life in Nov 2022</li>
<li class="fragment fade-in-then-semi-out">There will be an Extended support option</li>
</ul>

Note:

- Extended support will likely require either a paid subscription or self serve

---

### Is 2 years too soon?

<img src="./images/drupal9-10.svg" alt="Drupal 9 to Drupal 10" />

---

### No

We need to give people time to upgrade

---

### So what's driving this?

<p class="fragment">🥜 In a nutshell - security</p>

---

### Drupal 8

<div class="box-with-points">
<div class="box">
<h4>Drupal 8</h4>
<p>Symfony 3</p>
<p>PHP 7.0+</p>
<p>CKEditor 4</p>
</div>  
<div class="points">
<ul>
<li class="fragment">Symfony 3 EOL - <span class="underline">Nov 2021</span></li>
<li class="fragment">PHP 7.0 EOL - <strong>Jan 2019</strong></li>
</ul>
</div>
</div>

---

### Drupal 9

<div class="box-with-points">
<div class="box">
<h4>Drupal 9</h4>
<p>Symfony 4</p>
<p>PHP 7.3+</p>
<p>CKEditor 4</p>
</div>
<div class="points">
<ul>
<li class="fragment">Symfony 4 EOL - Nov 2023</li>
<li class="fragment">PHP 7.3 EOL - Dec 2021</li>
<li class="fragment">CKEditor 4 EOL - <span class="underline">Nov 2022</span></li>
</ul>
</div>
</div>

---

### Drupal 10

<div class="box-with-points">
<div class="box">
<h4>Drupal 10</h4>
<p>Symfony 5 or 6*</p>
<p>PHP 8.0 or 8.1*</p>
<p>CKEditor 5</p>
</div>
<div class="points">
<ul>
<li class="fragment">Symfony - Nov 2025 vs 2027</li>
<li class="fragment">PHP - Nov 2023 vs 2024</li>
</ul>
</div>
</div>

<p class="small fragment fade-in">*🤞</p>

---

### Noticing a pattern here?

<p class="fragment">Dependencies are driving our release dates</p>
<p class="fragment">We're one major release behind Symfony</p>

---

### Chapter 2: Where are we going?

---

### Drupal 11?

<p>💬Adopt a 2 year major release cycle and a <span class="underline">6 month LTS-to-LTS</span> overlap period for Drupal 10 and beyond</p>
https://drupal.org/node/3238652

Note:
- Let's unpack that a bit
- We've had 6 monthly minors since 8.0
- But no certainty for majors

---

### Now: Minor updates

<div class="box-with-points">
<div class="box">
<h4>Drupal 9.1.0</h4>
<p class="fragment">🐣 Dec 2020</p>
<p class="fragment">🪦 Nov 2021</p>
</div>
<div class="points">
<p class="fragment">You must update <span class="underline">once a year</span></p>
</div>
</div>

---

### What we're proposing*

<div class="box-with-points tall">
<div class="box">
<h4>Drupal 10.0</h4>
<p>🐣 June 2022</p>
</div>
<div class="box fragment" data-fragment-index="5">
<h4>Drupal 10.4</h4>
<p>🐣 Mar 2024</p>
<p class="fragment" data-fragment-index="7"><strong>🪦 Sep 2026</strong></p>
</div>
<div class="box fragment" data-fragment-index="1">
<h4>Drupal 11.0</h4>
<p>🐣 June 2024</p>
</div>
<div class="box fragment" data-fragment-index="4">
<h4>Drupal 11.4</h4>
<p>🐣 Mar 2026</p>
<p class="fragment" data-fragment-index="8"><strong>🪦 Sep 2028</strong></p>
</div>
<div class="box fragment" data-fragment-index="2">
<h4>Drupal 12.0</h4>
<p>🐣 Jun 2026</p>
</div>
</div>

<h4 class="small remove fragment fade-in-then-out" data-fragment-index="3">Regular 2 year majors</h4>
<h4 class="small remove fragment fade-in-then-out" data-fragment-index="6">LTS release 3 months before next major</h4>
<h4 class="small remove fragment fade-in-then-out" data-fragment-index="9">6 month overlap between LTS releases</h4>


<p class="small fragment fade-in">*Assuming https://drupal.org/node/3238652 gets consensus</p>

---

### What we're proposing*

<div class="box-with-points">
<div class="box">
<h4>Drupal 10.4.0</h4>
<p class="fragment">🐣 Mar 2024</p>
<p class="fragment">🪦 Sep 2028</p>
</div>
<div class="points">
<p class="fragment">You must update once every <span class="underline">four</span> years</p>
</div>
</div>

<p class="small fragment fade-in">*Assuming https://drupal.org/node/3238652 gets consensus</p>

---

### Disclaimers

<ul>
<li class="fragment">Hinges on releasing Drupal 10 on Symfony 6.0</li>
<li class="fragment">Assumes our other dependencies play nice</li>
</ul>

---

<!-- .slide: data-transition="fade" -->

<h3>What's coming in Drupal 10</h3>

---

<!-- .slide: data-transition="fade" -->

<h3><del>What's coming in Drupal 10</del></h3>

Note:
- Stop thinking that way

---

<!-- .slide: data-transition="fade" -->

### What's coming in Drupal 9.3?

<ul>
<li class="fragment">Bundle classes</li>
<li class="fragment"></li>
</ul>

Note:
- Start thinking this way
- We build Drupal 10 in Drupal 9
- We build Drupal 11 in Drupal 10

---

### Drupal 10.0 will be boring

* 9.4 minus deprecations
* Easier again to upgrade

---

### What about in Drupal 10.x?

- talk about initiatives

---

### New frontend theme

---

### Decoupled menus

---

### Project browser

Why is this important? Global training day

---

### Easy out of the box

---

### Automatic updates

---

### Starter kit theme

---

### User facing dependencies

ckeditor 5

---

### Lower level plumbing

php, symfony, composer, db versions

---

### 2 year cycles become the norm

link to issue, talk about reasons

---

### Remove jquery /jquery ui /backbone

---

### Chapter 3: Where do we need to go?

---

### Contributions are down

Covid is a factor, but no new faces are also an issue
Barrier to entry is higher, as a user and a contributor
We need to be bringing in fresh faces
Global talent shortages
Many of these initiatives point to that
But the reality is, the web landscape has changed
Monolith CMSs are less attractive
Decoupled menus sets us up for the future
Talk about NPM packages
Javascript is eating the Web
Atwood's law
JSON:API is a start but there are many places where API is second class citizen to theme/form apis

---

### Credits

- https://flickr.com/photos/tgerus/3807995646
- http://slides.com/gaborhojtsy/state-of-drupal-10-readiness-sept-2021
