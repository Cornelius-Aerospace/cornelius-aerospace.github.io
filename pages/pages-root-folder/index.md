---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#

layout: frontpage

header:
    title: Touching space; One leap at a time
    background-color: "#EFC94C;"
#    pattern: pattern_concrete.jpg
    image_fullwidth: earth-from-space.jpg
    
widget1:
  title: "Blog & Updates"
  url: "http://corneliusaerospace.co.uk/blog"
  image: widget-1-302x182.jpg
  text: "Follow our updates, early insights into upcoming videos, genuine design info as well as <em> our engineers rants about the existential philosophy of rocketry... (we are trying to stop her) </em>"
widget2:
  title: "What are we working on and what are our goals?"
  url: "http://corneliusaerospace.co.uk/info"
  text: "<em>Cornelius Aerospace</em> is heavily focoused on pushing the boundaries of amature-rocketry through iterative design, and <b> LOTS</b> and <b>LOTs</b> of <s>failures</s> <i>lessons</i> - we embrace (and swear at, in the moment) failures to extract as much progress out of our flights! Click to read more about our way of working and broad goals!"
widget3:
  title: "Keep up to date with our launches on the website, socials but best of all <b>YouTube</b> (our main platform)"
  url: "https://www.youtube.com/channel/UC06OHpXn2_ql_2xGfvBd0jA"
  image: widget-github-303x182.jpg
  text: "<em>YouTube</em> is where we post our footage, but click on the button below to join our mailing list, where we send out information about changes, launches and project progress before updating youtube or the site. It's like an insider view - but completly free (and we will never spam you or share your details, we wish the people who choose to do that a bag of dicks and a bad rocket flight!)"
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
callforaction:
  url: https://mailbob.io/u/corneliusaerospace
  text: Keep me upto date!
  style: alert




permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true


# I am yet to learn what the html below does but without it the page goes "poof" and seems to disapear.
# Websites arnt my thing.... - Leah
---


<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
