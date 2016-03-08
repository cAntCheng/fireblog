fireblog
===

intro
---
A github pages Blog system powered by AngularJS and Firebase and Bootstrap.

[中文说明](http://cheng-kang.github.io/#/p=1457398271740)

[Instruction English Version](http://cheng-kang.github.io/#/p=1457399976958)

[AngularJS](https://angularjs.org/)

[Firebase](https://www.firebase.com/)

[Bootstrap](http://getbootstrap.com/)

[Clean Blog](http://startbootstrap.com/template-overviews/clean-blog/)

instruction
---

1 log in with github account

![login](http://7u2sl0.com1.z0.glb.clouddn.com/fireblog_login_with_github.png)

2 find the uid

![config page](http://7u2sl0.com1.z0.glb.clouddn.com/fireblog_config_page.png)

3 edit the config.js file

![set config](http://7u2sl0.com1.z0.glb.clouddn.com/fireblog_config.png)

4 you can now manage your blogs here

![archives](http://7u2sl0.com1.z0.glb.clouddn.com/fireblog_archives.png)


development
---
Basic Routing Structure:

- home: show article list by page
- articles: show the timeline
- cats: show all cat-tags
- tags: show all article tags

- article=:id: show a certain article
- cat=:id: show article list in a certain category
- tag=:id: show article list with a certain tag

- admin: admin panel
- admin/articles: article list with add/edit/delete operation buttons
- admin/post: post a new article
- admin/edit=:id: edit an article
-admin/login: login page

Database Structure:
- :userid-articles:
  - $id
  - title
  - cat
  - tags
  - content
  - date
  - conments
- :userid-tags
- :userid-cats
- users

-----------
to-do:
- check if the data is still bound to the firebase data when it's added to a new array.
