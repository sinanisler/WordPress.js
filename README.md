# WordPress.js


![](https://img.shields.io/badge/Status-Under_Development-orange.svg)

![](https://img.shields.io/badge/WordPress-blue.svg) 
![](https://img.shields.io/badge/JS-yellow.svg)
![](https://img.shields.io/badge/React-yellow.svg)
![](https://img.shields.io/badge/REST-pink.svg)


WordPress Theme working on warp speed.


### ✔ Stack
React + REST + Maybe WPGraphQL + WordPress


### ✔ Info
Most of the users or developers (like me) doesnt want to maintain two or more servers.

Why not make a modern WordPress Theme but use just one server ?

This is why i wanted to make this theme. 

If you dont need Headless just dont make it. 

![](https://raw.githubusercontent.com/sinanisler/sinanisler/master/img/headless-cms.jpg)


### Plan
Plan is making the one WordPress server and making React work only client side.
Using React with WP REST or GraphQL data point.
WordPress will render bare minimum html for the crawlers but React will hide on users.
If crawlers visit it will see html and if user visit will render the theme.


### ✔ Flow
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
 HTML         React Render
```

### ✔ WordPress Hierarchy
Theme will support basic WordPress Hierarchy functions and flow.

![](https://raw.githubusercontent.com/sinanisler/sinanisler/master/WordPress-Hierarchy-v2.png)
