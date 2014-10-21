rawpixel
========

Rob Churchill assets portal kickstart

This is the backend piece of the web portal itself which will utilize Symfony2 components.





Phase 1 web based file manager internal users

Web Based File Manager 

presentation - css3, html5, library(jquery) template(twig), symfony2 bundle (treebrowser) (http://symfony.com/doc/master/cmf/bundles/tree_browser/introduction.html)
  
  /drag and drop image files lower left section
  /left hand filtering above node hierarchy - 
  /left hand nodes and subnodes which can accept drag and drop of other nodes
  /right hand file breadcrumb type display above gallery panel
  /right lower assets gallery panel - displays images in current selected directory
  /javascript links appearing on hover of images in assets gallery
  /multiselect images to drag into left panel nodes
  
process:  
  /symfony2 bundle treebrowser custom mod
  /mysql and doctrine - create tables for image assets with references to web server locations and foreign key to metadata and owners and acl tables repectively.
  /ajax and json
  /htaccess mod for staging -u and -p
  /basic site scafolding symfony2, routes, mysql, apache local
  /create sql for filtering, image crud, joins, acl, metadata crud
  /file retrieval/writing for image assets to web server repo
  
  
