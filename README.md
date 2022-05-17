# WordPress.js


![](https://img.shields.io/badge/Status-Under_Development-orange.svg)
![](https://img.shields.io/badge/WordPress-blue.svg) 
![](https://img.shields.io/badge/JS-yellow.svg)
![](https://img.shields.io/badge/React-yellow.svg)
![](https://img.shields.io/badge/REST-pink.svg)


WordPress Theme working on Warp Speed.

Planned Stack: React + REST + Bootstrap + WordPress



### Planned Details

Why not make a modern React WordPress Theme but use just one server ?

This is why i wanted to make this theme. 

Lets see how fast a native theme can be.

Apache, Ngnix or Litespeed is not slow bad code is slow...


### Plan
Plan is making the one WordPress server and making React work only client side.
Using React with WP REST or GraphQL data point.
WordPress will render bare minimum html for the crawlers but React will render on users.
If crawlers visit it will see html and if user visit will render the theme. 
The aim is making SEO as powerfull as a WordPress native theme.


### Flow
```
       WordPress 
           |
           |
           v
  React + REST + Cache
           |
           |
       ____|____
If BOT          IF User
  |               |
 HTML           React 
```

### WordPress Hierarchy
Theme will support basic WordPress Hierarchy functions and flow.

![](https://raw.githubusercontent.com/sinanisler/sinanisler/master/WordPress-Hierarchy-v2.png)




### Power

![](https://user-images.githubusercontent.com/1686324/167460147-a738bf38-7451-4984-acb7-1bc893cce2c3.gif)



