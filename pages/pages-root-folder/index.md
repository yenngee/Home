---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: Data_Sciencing_header.jpg
widget1:
  title: "About Me"
  url: 'https://yenngee.github.io/datasciencing/info/'
  image: widget-1-302x182.jpg
  text: 'I am an aspiring data analyst...'
widget2:
  title: "Portfolio"
  url: 'https://yenngee.github.io/datasciencing/portfolio/'
  text: 'What? How? Why? These are the questions I hope to answer through my projects.'
  image: widget_portfolio_1.jpg
widget3:
  title: "Ramblings"
  url: 'https://yenngee.github.io/datasciencing/blog/'
  image: widget_blog_cut.jpg
  text: 'Two cents worth of thoughts and ramblings on data-related topics.'
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
# callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
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
