# WordPress.js


![](https://img.shields.io/badge/Status-Under_Development-orange.svg)
![](https://img.shields.io/badge/WordPress-blue.svg) 
![](https://img.shields.io/badge/JS-yellow.svg)
![](https://img.shields.io/badge/React-yellow.svg)
![](https://img.shields.io/badge/WPGraphQL-pink.svg)


WordPress Theme working on warp speed.


### ✔ Stack
React + WPGraphQL + WordPress


### ✔ Why
Mst of the users or developers (like me) doesnt want to maintain two or more servers.

Why not make a modern WordPress Theme but use just one server ?

This is why i wanted to make this theme. 

I think this maybe the new way of making WordPress Themes too.


### ✔ Reasoning

Right now making a headless WordPress means giving up lots of plugins, theme features, speed optimizations, SEO and core features.

Literaly we are cutting the head off one of the greatest open soruce software and putting in somewhere else. 

Why not use both worlds best features and combine it ?

If you dont need Headless just dont do it. You will just create more problems than solution.

![](https://raw.githubusercontent.com/sinanisler/sinanisler/master/img/headless-cms.jpg)


### Plan
Plan is making the WordPress Server the only server and making React .jsx only on client side.
Using React with GraphQL making the render on client side only.
WordPress will render bare minimum html for the crawlers but React will hide on users.
If crawlers visit they will see read html and if user visit they will render the theme.



### ✔ Flow
```
       WordPress 
           |
           |
           v
   React + GQL + Cache
           |
           |
       ____|____
If BOT          IF User
  |               |
 HTML         React Render
```

### ✔ WordPress Hierarchy
Theme will support basit WordPress Hierarchy functions and flow.

![](https://raw.githubusercontent.com/sinanisler/sinanisler/master/WordPress-Hierarchy-v2.png)
