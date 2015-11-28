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
  title: "Hair by Leah"
  url: ''
  image: widget-1-302x182.jpg
  text: 'Leah Rieger is one of the Mizu stylists that will help you look and feel better.'
widget2:
  title: "Hair By Roo"
  url: ''
  text: 'Ricka Taylor is one of the Mizu stylists that will help you look and feel better.'
widget3:
  title: "H9 Water"
  url: 'https://www.h9water.com/public/index.aspx'
  image: widget-github-303x182.jpg
  text: 'We at H9 Water understand the role water plays in achieving optimal health. It is with this understanding that has allowed us to continually invest in water research, which in turn has allowed us to produce one of the most beneficial, scientifically-backed water products ever created.'
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
  url: /contact.html
  text: Schedule an Appointment ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---