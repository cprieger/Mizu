---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
#widget1:
#  title: "Blog & Portfolio"
#  url: 'http://mizulubbock.com/blog/'
#  image: widget-1-302x182.jpg
#  text: 'Keep up to date with all the latest trends and fashions by reading our blog.'
widget1:
  title: "Where are we located?"
  url: 'http://mizulubbock.com/location/'
  image: tourist-map.jpg
  text: 'Located off of Loop 289 between Furrs and the Science Spectrum.'
widget2:
  title: "What are the prices?"
  url: 'http://mizulubbock.com/info/'
  image: old-register.jpg
  text: 'Our prices are listed in the info section of the website.'

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
  url: http://mizulubbock.com/contact
  text: Schedule an appointment ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---