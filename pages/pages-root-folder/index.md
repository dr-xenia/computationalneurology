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
  title: "Read about our research"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: 'In the research group, we seek to answer clinical relevant questions in the field of neuropsychiatry using computational methods. In Computational Neurology, we interlink imaging methodology with clinical data.'
widget2:
  title: "Meet Prof. Kobeleva"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  text: 'Xenia Kobeleva is an assistant professor (tenure track) in Neurostimulation at Ruhr University Bochum (faculty of medicine). She is an expert in neurodegenerative diseases and brain modeling and conducts translational research, focusing on impactful research questions.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Get to know the team"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: "The research groupss diverse team consists of physicians, experts in informatics, and basic sciences. We conduct interdisciplinary research at the intersection of mathematics, informatics, and neuroscience."
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
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
Testinggg
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
