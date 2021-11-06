
## Drupal 10 and beyond

Note:
- welcome
- make yourself comfortable good program of sessions coming up
- recognise a lot of the names in the attendee list, and I think that's a problem, but we'll get to that later

---

### About me

@larowlan

<img src="./images/avatar2.jpg" alt="avatar" class="img--offscreen" />

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

- fragments*
- two part informative
- one part my typical navel gazing exercise
- i hope you come away with some things to mull over

---

# Where are we?

---

### Drupal 10 will come out <span class="underline">next year</span>

---

### Release cycle

<h4 class="small remove fragment fade-in-then-out" data-fragment-index="1">Drupal 10 (and 9.4) will come out <span class="underline">next year</span></h4>
<h4 class="small remove fragment fade-in-then-out" data-fragment-index="2">Drupal 9.3 will be out <span class="underline">next month</span></h4>
<h4 class="small remove fragment fade-in-then-out" data-fragment-index="3">Drupal 8 is <span class="underline">EOL</span></h4>
<h4 class="small remove fragment fade-in-then-out" data-fragment-index="4">Drupal 7 is <span class="underline">EOL next year</span></h4>

<div class="box-with-points tall">
<div class="box fragment" data-fragment-index="4">
<h4>D7</h4>
<p>🐣 Jan 2011</p>
<p><strong>🪦 Nov 2022</strong></p>
</div>
<div class="box fragment" data-fragment-index="3">
<h4>D8</h4>
<p>🐣 Jan 2015</p>
<p><strong>🪦 Nov 2021</strong></p>
</div>
<div class="box fragment" data-fragment-index="2">
<h4>9.3</h4>
<p>🐣 Dec 2021</p>
</div>
<div class="box fragment" data-fragment-index="1">
<h4>9.4</h4>
<p>🐣 2022</p>
</div>
<div class="box fragment" data-fragment-index="1">
<h4>10.0</h4>
<p>🐣 Jun 2022</p>
</div>
</div>


Note:
- D10: June 15, Aug 16, Dec 14, may be a 9.5
- D9.3: please help us test the pre-releases
- D8 came out in 2015, 6 years ago, iphone 6 was the latest
- D7 came out in 2011, 10 years ago, iphone 4 was the latest
- There will be a paid extended support option available from vendors

---

### 🧚 Updating between major versions is much easier

https://pnx.me/3C6v3kH

Note:

- Provided you're on Drupal 8

---

### Is 2 years too soon?

<img src="./images/drupal9-10.svg" alt="Drupal 9 to Drupal 10" />

---

### No

We need to give people time to upgrade

---

### So what's driving this?

<ul>
<li class="fragment">EOL dates for dependencies</li>
<li class="fragment">We're one major release behind Symfony</li>
</ul>

Note:
- One major SF behind shortens our window

---

### Security support of dependencies

<div class="box-with-points">
<div class="box fragment" data-fragment-index="1">
<h4>Drupal 8</h4>
<p><strong>Symfony 3</strong></p>
<p>PHP 7.0+</p>
<p>CKEditor 4</p>
</div>  
<div class="box fragment" data-fragment-index="2">
<h4>Drupal 9</h4>
<p>Symfony 4</p>
<p>PHP 7.3+</p>
<p><strong>CKEditor 4</strong></p>
</div>
<div class="box fragment" data-fragment-index="3">
<h4>Drupal 10</h4>
<p>SF 5 or 6*</p>
<p>PHP 8.0 or 8.1*</p>
<p>CKEditor 5</p>
</div> 
</div>

<p class="small remove fragment fade-in-then-out" data-fragment-index="1">Symfony 3 EOL <span class="underline">Nov 2021</span></p>
<p class="small remove fragment fade-in-then-out" data-fragment-index="2">CKEditor 4 <span class="underline">Nov 2022</span></p>
<p class="small remove fragment fade-in-then-out" data-fragment-index="3">*All things going to plan</p>

Note:
- So the EOL for Drupal 8 co-incides with EOL of symfony 3
- actually, symfony extended security support for Sf 3 after Alex Pott and I joined their security team to help with backporting 
- CKEditor is driving the Drupal 9 release date
- We want 10 out at least 6 months before EOL for CKEditor 4
- For D10, difference between sf5 and 6 is an extra 2 years

---

# Where are we going?

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
<p class="fragment">🪦 Dec 2021</p>
</div>
<div class="points">
<p class="fragment">You must update <span class="underline">once a year</span></p>
</div>
</div>

Note:
- to be running a security supported version

---

### What we're proposing*


<h4 class="small remove fragment fade-in-then-out" data-fragment-index="1">Regular <span class="underline">2 year</span> majors</h4>
<h4 class="small remove fragment fade-in-then-out" data-fragment-index="4">LTS release <span class="underline">3 months</span> before next major</h4>
<h4 class="small remove fragment fade-in-then-out" data-fragment-index="7"><span class="underline">6 month</span> overlap between LTS releases</h4>

<div class="box-with-points tall">
<div class="box">
<h4>Drupal 10.0</h4>
<p>🐣 June 2022</p>
</div>
<div class="box fragment" data-fragment-index="6">
<h4>Drupal 10.4</h4>
<p>🐣 Mar 2024</p>
<p class="fragment" data-fragment-index="8"><strong>🪦 Sep 2026</strong></p>
</div>
<div class="box fragment" data-fragment-index="2">
<h4>Drupal 11.0</h4>
<p>🐣 June 2024</p>
</div>
<div class="box fragment" data-fragment-index="5">
<h4>Drupal 11.4</h4>
<p>🐣 Mar 2026</p>
<p class="fragment" data-fragment-index="9"><strong>🪦 Sep 2028</strong></p>
</div>
<div class="box fragment" data-fragment-index="3">
<h4>Drupal 12.0</h4>
<p>🐣 Jun 2026</p>
</div>
</div>


<p class="small fragment fade-in">*Assuming https://drupal.org/node/3238652 gets consensus</p>

---

### What we're proposing*

<div class="box-with-points">
<div class="box">
<h4>Drupal 10.4.0</h4>
<p class="fragment">🐣 Mar 2024</p>
<p class="fragment">🪦 Sep 2026</p>
</div>
<div class="points">
<p class="fragment">You must update once every <span class="underline">two and a half</span> years</p>
</div>
</div>

<p class="small fragment fade-in">*Assuming https://drupal.org/node/3238652 gets consensus</p>

---

### Disclaimers

<ul>
<li class="fragment">Hinges on releasing Drupal 10 on <span class="underline">Symfony 6.0</span> and <span class="underline">PHP 8.1</span></li>
<li class="fragment">Assumes our other dependencies play nice</li>
</ul>

Note:
- We may need to fork/backport/shim

---

<!-- .slide: data-transition="fade" -->

<h3>What's coming in Drupal 10</h3>

---

<!-- .slide: data-transition="fade" -->

<h3><del>What's coming in Drupal 10</del></h3>

Note:
- Stop thinking that way

---

<!-- .slide: data-transition="fade" class="twocol" -->

### What's coming in Drupal 9.3?

<ul>
<li class="fragment">PHP 8.1 support</li>
<li class="fragment">Bundle classes</li>
<li class="fragment">Manage permissions tab</li>
<li class="fragment">Generic revision access</li>
<li class="fragment">CKEditor 5*</li>
<li class="fragment">Olivero/Claro stable*</li>
</ul>

<p class="small fragment fade-in">*All things going to plan</p>

Note:
- Start thinking this way
- We build Drupal 10 in Drupal 9
- We build Drupal 11 in Drupal 10

---

### Manage permissions tab

<img src="./images/perms-tab.png" alt="manage permissions tab" />

---

### CKEditor 5

<img src="./images/ckeditor5.png" alt="ckeditor5" />

---

<!-- .slide: class="twocol" -->

### What's coming in Drupal 9.4?

<ul>
<li class="fragment">Olivero/Claro stable</li>
<li class="fragment">Forum/Hal/Aggegator/Quickedit moved to contrib</li>
<li class="fragment">Decoupled menus module*</li>
<li class="fragment">Expanded JSON:API revision support*</li>
<li class="fragment">Generic revision UI*</li>
<li class="fragment">New autocomplete/dialog*</li>
</ul>

<p class="small fragment fade-in">*All things going to plan</p>

Note:
- Deprecations until D11 except the modules going to contrib
- Moving away from jQuery UI

---

### Olivero

<img src="./images/OliveroDrupal10.jpeg" alt="olivero" />

---

### Drupal 10.0 will be boring

<ul>
<li class="fragment">9.4 minus deprecations</li>
<li class="fragment"><span class="underline">Easier</span> again to upgrade</li>
</ul>

Note:
- For those of you still on D7 this will be cold comfort but we've learnt from that process

---

### Moving to D10

<img src="./images/d10-state.png" alt="Drupal 10 state" />

Note:
- Much of the work to move to update D9 code D10 can be automated.

---

### What about in Drupal 10.x?

🎁 This is where the goodies start

Note:
- In this new way of thinking, this is how we build Drupal 11

---

### Automatic updates

<ul>
<li class="fragment">✅PSAs in UI</li>
<li class="fragment">✅Readiness checks API</li>
<li class="fragment">✅Signing updates</li>
<li class="fragment">✅Applying updates with rollback</li>
<li class="fragment">⏳Composer based updater</li>
</ul>

---

### Automatic updates

<img src="./images/updates.png" alt="automatic updates" />

Note:
- a lot of people in this call will be thinking this isn't for me
- govcms etc

---

### Project browser

<img class="fragment" src="./images/project-browser.png" alt="project browser" />

Note:
- Work happening in contrib
- Join the team
- Will build on top of automatic updates to work with composer under the hood

---

### Easy out of the box

<ul>
<li class="fragment">Layout builder</li>
<li class="fragment">Media</li>
<li class="fragment">Claro</li>
</ul>

Note:
- enabling these in standard profile
- my opinions on standard profile are well known, see my session from Drupal South gold coast
- Umami profile has shown this is possible
- We want people starting their sites with a good foot forward

---

### Starter kit theme

drupal.org/node/3050378

Note:
- those of you who've been around long enough would remember zen theme's commands for generating a new theme
- its the same concept
- we'd deprecate and remove classy/stable
- it allows us to change template markup to fix bugs without breaking people's sites

---

### jQuery

<ul>
<li class="fragment">☠️ Continue the jQuery death march</li>
<li class="fragment">drupal.org/node/3238306</li>
</ul>

Note:
- we are progressively turning on no-jquery eslint rules
- there are a load of easy issues to get involved in
- great for tomorrow's code sprint!!

---

# Where do we need to go?

Note:
- This commences the navel gazing part of the talk
- I hope this prompts some really lively Q and A

---

### If dependencies drive our EOL? 

<ul><li class="fragment">Was getting off the island the right thing to do?</li>
<li class="fragment">Does the fact D7 is still kicking indicate so?</li>
</ul>

Note:
- To an outsider this may seem to be the case
- But the reality is core devs are stretched thin maintaining code we wrote
- Let alone adding all this other code we don't even have to think about

---

### How core development works

Note:
- How people think it works (well planned out backlog, priorities are decided)
- How it actually works (organisations bring their ideas and progress them to fruition)
- Acquia is the exception, they fund things that probably don't help their business, but do help the ecosystem
- e.g. Lullabot identified need with Olivero and drove that
- but locally ServiceNSW, NSW Dept of Customer Service and PreviousNext have driven a lot of the big changes in 9.3 like revision
- not everyone knows enough about Drupal to contribute patches but there are other ways to contribute and you can always sponsor someone to bring a feature to fruition
- To use a cliche the rising tide lifts all boats

---

> I'm rapidly discovering that what I thought was a large group of people working together to guide Drupal core is a lot smaller than I once thought.
 - Max Pognowski

Note:
- The reality is contribution comes from a small pool.
- Core is so vast
- There are some subsystems that I can count on one hand the number of people who have a deep knowledge of how it works
- There are some parts of core where the loss of a single individual would cause progress to grind to a halt 

---

> For an ecosystem that provides gainful employment to so many, so much work falls to so few
- Me

---

### MAINTAINERS.TXT

has some large holes

Note:
- there are whole systems in core with no listed maintainer
- people pitch in here and there
- but if your business relies on this piece of core, perhaps you could step up and help out?

---

### Contributions are down

<p class="fragment">10% decline in <span class="underline">individual</span> contributors</p>
<p class="fragment">2% decline in <span class="underline">organizational</span> contributors</p>

Note:
- Covid is a factor, but no new faces are also an issue

---

### Business is booming

<img class="fragment" src="./images/business-chart.png" alt="growth expectations" />

Note:
- source: Drupal Business Survey 2021
- Less sites, but bigger budgets
- You can see that in the D7 vs D8 usage stats
- There are more installs of D7 jQuery update than all D8 and 9 sites.

---

### Certified Drupal Partners program

Note:
- DA trying to address this imbalance
- Recognise orginisations who contribute back
- Strong exposure Vs None

---

### Talent is scarce

Note:
- Anyone hiring lately, its hard
- The pool of faces isn't growing
- Oxide, PreviousNext, Salsa, NSW Department of customer service
- Check the #jobs channel
- developers want to work where contribution is part of an org's DNA

---

### Barriers to entry

Note:
- Think about how you got started
- Myself I built small sites for local businesses
- Bigger projects have less opportunties for that
- The drupal association has a new mentoring program
- There is so much prior knowledge required just to be productive
- initiatives like project browser help
- the last global training day I ran, I avoided talking about adding modules to the site because its a minefield
- this used to be a major selling point 'there's a module for that'
- but now its too complex to cover in a single day's training

---

### JavaScript is eating the web

Note: 
- The web landscape has changed
- Atwood's law "anything that can be written in javascript will eventually be written in javascript"
- Decoupled CMS as a service offering are coming up fast behind us
- Entry to this space is much simpler
- 10 years ago small agency Cpanel

---

### Decoupled menus initiative is a step in the right direction

Note:
- Work out how to ship npm packages
- Work out tooling for non PHP projects
- Gitlab features like pages, CI, publishing to NPM
- Once library is using it
- JSON:API is a start but there are many places where API is second class citizen to theme/form apis
- Stuart and Nuxt is doing some amazing work on this front
- I spoke about this topic at length at Decoupled days

---

### What can we as an AU/NZ community do?

Note:
- What can we do locally to improve attracting new users to the project
- Where are the entry level conferences?
- Vlad in Brisbane at the TAFE
- Murray in Sydney working with TAFE
- NZ meetup committee were talking about this too
- Maybe sprint day tomorrow? Max became a regular contributor after the last one, maybe you could too?

---

### Credits

- http://slides.com/gaborhojtsy/state-of-drupal-10-readiness-sept-2021
