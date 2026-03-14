---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header-ondes-internes.jpg
widget1:
  title: "Bar Radis"
  url: '/bar_radis/'
  image: bar_radis/marbre.jpg
  text: "Vous avez toujours rêvé de manger des expériences ? C'est ce qui s'est passé au Bar Radis en avril 2025 : nous sommes intervenu·e·s pour parler océan et glaciers pendant un repas où les convives reproduisaient l'expérience dans leur assiette !"
widget2:
  title: "Tribulations savantes"
  url: 'tribulations_savantes'
  image: tribulations_savantes/affiche_tribus.png
  text: 'Que vous soyez scientifique en herbe, curieux·se, ou tout simplement perdu·e sur le campus saint Martin d’Hères le lundi 27 avril 2026, les Tribulations Savantes sont faites pour vous !'
widget3:
  title: "Projet Casemate"
  url: 'projet_casemate'
  image: projet_casemate/maquettes_finales.jpeg
  text: "Nous avons eu la chance durant d'être invité au FabLab de la Casemate (qui est un organisme de médiation scientifique et culturelle à Grenble) pour réaliser une nouvelle maquette de médiation scientifique sur l'océanographie."
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
#   url: https://tinyletter.com/feeling-responsive
#   text: Inform me about new updates and features ›
#   style: alert
# permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
permalink: /
---
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
