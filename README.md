# WordPress.js
![](https://img.shields.io/badge/Status-Under_Development-orange.svg)
![](https://img.shields.io/badge/WordPress-blue.svg) 
![](https://img.shields.io/badge/JS-yellow.svg)

Ultimate goal making a WordPress Theme working faster than Headless WordPress


### ✔ Stack
React + WPGraphQL + WordPress


### ✔ Why not Headless?
Headless have its own use but most of the developers doesnt have to own two or more servers.

Why not make a modern WordPress Theme but use just one server ?



### Plan
Plan is making the WordPress Server the only server and using React only client side.
Using React with GraphQL making the render on client side only.
WordPress will render basit html for the crawlers but react will hide and check the bots.
If bots visits they will see basic html if user visits they will render the website.


### ✔ Flow
```
       WordPress 
           |
           |
           v
     React + WP Theme
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
