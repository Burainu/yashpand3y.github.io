---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: momentum_main_screen_1600x503.png
widget1:
  title: "Dev Blog Updates!"
  url: 'https://yashpand3y.github.io/yashpand3y.github.io/dev-blogs/'
  image: unity_logo_302x182.png
  text: 'Follow along with our development process with weekly blog updates from the developers of the game itself! Watch as the game development picks up <em>Momentum</em> and brings Hiro to life in his quest to save the world.'
widget2:
  title: "GitHub Repo"
  url: 'https://github.com/hoalexander44/MomentumGame'
  image: widget-github-303x182.jpg
  text: '<em>Momentum</em> repository can be viewed by clicking here! Follow along with the devs to get an idea of what this game looks like behind the scenes'
  
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
