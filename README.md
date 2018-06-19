
# Content Management System Interface

This is a multi-page, content management system interface, featuring updatable fields and an embedded text editor. 

![](https://raw.githubusercontent.com/CLewisMessina/Content_Management_System/master/img/CMS.png)

**Code base:** HTML, CSS, JavaScript

**JS Libraries:** Bootstrap v3.3.7 (incl. jQuery), CKEditor

**Visual Components:** glyphicons (fonts/icons)

**Code Tools:** MS Visual Studio Code

**Working Example:** https://clewismessina.com/content_mgt_system/


### PROJECT HIGHLIGHTS
I've worked with WordPress's content management system (CMS) many times, but had never put together my own CMS interface prior to this. 

On one hand, the concept is simple: you have content, make a gadget to edit it. 

On the other hand, have you ever considered everything that a content management system requires? email, security, user management, analytics, blog posts, scalability...

All of these are challenges to anyone wanting to forego a pre-built like WordPress, Drupal, Shopify, et. al.

I was impressed at how helpful Bootstrap can be, with it's ready made objects there for the plucking and altering. I was also impressed at how easy CKEditor makes it to embed a text editor within your code. I absolutely loved seeing everything that makes a CMS tick and considering further refinements after the fact.


## REFACTOR NOTES


### Redundancy
I would remove redundant visual elements (e.g. breadcrumbs). I'd also like to take a stab at putting in a back-end to this and porting it to Heroku or Cloud9 as a Node/Express driven project.

### CSS
Bootstrap is a double edged sword: it allows one to quickly build a site, but at the sacrifice of customization and personality- unless you really enjoy a heavy does of !important in your CSS. Given a refactor, I'd use flex-box and pure CSS for all styling. I'd also add some animation to buttons and just update the look in general.

### HTML
Since this project, I've come across Lea Verou's <a href="http://mavo.io/" target="_blank">Mavo</a> project, which allows a lot of backend functionality within the HTML, including database CRUD operations. I think applying mavo would make this much lighter in terms of code.


