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
  title: "工程案例"
  url: '／projects/'
  image: widget-1-302x182.jpg
  text: '一些<em>良明设计事务所</em>以往做过的项目.'
widget2:
  title: "服务范围"
  url: '/info/'
  text: '<em>良明设计事务所</em>为您提供以下服务：<br/>1. 房屋住宅设计<br/>2. 室内装潢设计<br/>3. 商业店铺设计<br/>4. 政府报建审批申请<br/>5. 施工现场监理'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "发表文章"
  url: '/articals'
  image: widget-github-303x182.jpg
  text: '<em>良明设计事务所</em>首席设计师发表的一些文章。 <a href="http://twitter.com/liangdesign">@liangdesign</a>.'
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
  text: 如有更新请通知我 ›
  style: alert
permalink: /backup
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/fQaiZhNx8B0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
