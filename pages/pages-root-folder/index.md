---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage  
#
layout: frontpage
header:
  image_fullwidth: IMG_9085_elab_testata.jpg
widget1:
  title: "Blog & Portfolio" 
  url: '/foto/'
  image: IMG_9032_elab.jpg
  text: 'You can see my old photo on this site, but everyday I take  new photos. Are you looking for a particular photo. Just hire me, I will shoot the right photo for your business'
widget2:
  title: "Blog & Portfolio" 
  url: '/foto/'
  image: IMG_9032_elab.jpg
  text: 'In questo sito potete vedere le mie foto, anche se '
widget3:
  title: "Download Theme"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. Grab the <a href="https://github.com/Phlow/feeling-responsive/tree/bare-bones-version">Bare-Bones-Version</a> for a fresh start or learn how to use it with the <a href="https://github.com/Phlow/feeling-responsive/tree/gh-pages">education-version</a> with sample posts and images. Then tell me via Twitter <a href="http://twitter.com/phlow">@phlow</a>.'
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
  url: mailto:chiara@pedani.it?subject=I%20wont%20hire%20you.&cc=matteo@pedani.it&body=Send%20me%20more%20information%20on%20your%20work.
  text: 'contact me  - contattami' 
  style: alert
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
