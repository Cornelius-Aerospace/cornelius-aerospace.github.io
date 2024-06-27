---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Blog & Updates"
  url: "http://corneliusaerospace.co.uk/blog"
  image: widget-1-302x182.jpg
  text: "Follow our updates, early insights into upcoming videos, genuine design info as well as <em> our engineers rants about the existential philosophy of rocketry... (we are trying to stop her) </em>"
widget2:
  title: "What are we working on and what are our goals?"
  url: "http://corneliusaerospace.co.uk/info"
  text: "<em>Cornelius Aerospace</em> is heavily focoused on pushing the boundaries of amature-rocketry through iterative design, and <b> LOTS</b> and <b>LOTs</b> of <s>failures</s> <i>lessons</i> - we embrace (and swear at, in the moment) failures to extract as much progress out of our flights! <br/>1. Consutrction Methods<br/>2. FLight computer optimisation (small, dainty and packed with <b><i>DATA!</i></b>).<br/>3. Practising with weather balloons to explore the feasability of a rocketoon or a similar system (because propellant is <i>EXPENSIVE</i>)<br/>4. Experement with various designs (boosters, staging, larger motors, praying and licking special crystals... all the norm really) <br/>5. Optimising for altitude after other core features are refined, not much point getting to 10km and loosing the £1000 rocket that got there"
widget3:
  title: "Keep up to date with our launches on the website, socials but best of all <b>YouTube</b> (our main platform)"
  url: "https://www.youtube.com/channel/UC06OHpXn2_ql_2xGfvBd0jA"
  image: widget-github-303x182.jpg
  text: "<em>YouTube</em> is where we post our footage, but click on the button below to join our mailing list, where we send out information about changes, launches and project progress before updating youtube or the site. It's like an insider view - but completly free (and we will never spam you or share your details, we wish the people who choose to do that a bag of dicks and a bad rocket flight!)"
  callforaction:
    url: https://mailbob.io/u/corneliusaerospace
    text: Keep me upto date!
    style: alert
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
