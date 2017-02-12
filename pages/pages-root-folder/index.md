---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_0.jpg
widget1:
  title: "House Design"
  url: '/house-design'
  image: widget-1-302x400.jpg
  text: '<em>Liang Design Studio</em> provides design services for single family house, laneway house, and home renovation。'
widget2:
  title: "Interior Design"
  url: '/interior-design'
  image: widget-2-303x400.jpg
  text: 'Scope of services: programming and space planning, interior design, construction documents, and project administration.'
widget3:
  title: "Commercial Space"
  url: '/commercial-design'
  image: widget-3-303x400.jpg
  text: 'office spaces, retail spaces, restaurants, entertainment spaces, etc. Assist to apply construction permits from city hall'
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
  url: http://liangdesign.com
#  url: https://tinyletter.com/feeling-responsive
  text: ---------- if any inquiries, please call：778-300-1388 ----------
  style: alert
permalink: /
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: false
---
<div class="row t30">
	<div class="small-12 columns">
		<img src="{{ site.urlimg }}/liangdesign-home-01.jpg" width="970" alt="Liang design studio">
	</div><!-- /.small-12.columns -->
</div><!-- /.row -->
