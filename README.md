# WordPress.js
![](https://img.shields.io/badge/Status-Under_Development-orange.svg)
![](https://img.shields.io/badge/WordPress-blue.svg) 
![](https://img.shields.io/badge/JS-yellow.svg)
![](https://img.shields.io/badge/React-yellow.svg)
![](https://img.shields.io/badge/WPGraphQL-pink.svg)


Ultimate goal making a WordPress Theme working as static site speed.


### ✔ Stack
React + WPGraphQL + WordPress


### ✔ Why
Headless have its own use but most of the developers (like me) doesnt want to pay or maintain two or more servers.

Why not make a modern WordPress Theme but just use just one server ?

Why Not ?



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
