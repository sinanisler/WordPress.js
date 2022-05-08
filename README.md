# WordPress.js
![](https://img.shields.io/badge/Status-Under_Development-orange.svg)


### ✔ Stack
React + ReactDOM + WPGraphQL + WordPress

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
Ultimate goal of this project is supporting WordPress Hierarchy.

![](https://raw.githubusercontent.com/sinanisler/sinanisler/master/WordPress-Hierarchy-v2.png)
