---
layout: post
category : Reflective blog
tagline: "February 28, 2016"
author: Brian Yip
tags : [blog]
---
# React.js

Last week I met up with a group of ambitious web developers in ShiftKey Labs where we listened to a guest speaker talk about FaceBook's front-end web framework **React.js**. Below are some of the key concepts that were covered during the presentation:

* Tools like [webpack](https://webpack.github.io/) to bundle multiple dependencies into one single file and [Babel](https://babeljs.io/) to compile the React.js JSX and ES6 into ES5.
* React.js focuses on the **V** in the **MVC** pattern
* The framework is not too complicated since it allows developers to build a virtual DOM via rendered **components**
* The [Flux](https://facebook.github.io/flux/docs/overview.html) architecture for maintaining the state or each component

      ![React.js](https://facebook.github.io/react/img/logo_og.png) 

Overall, I had a great experience and figured out why I would want to use React.js over other front-end web frameworks like Angular.js. Because React.js has a modular nature where all components can be recycled to construct custom views, this makes it an excellent choice for building a scalable **SPA** (Single-Page-Application). However, frameworks that are tightly coupled with HTML like Angular.js would be better for smaller SPAs as the error messages tend to be more cryptic, and thus harder to debug.

Not only did I learn why I would use React over Angular, but I also learned about good web development practices like using **webpack** to bundle dependencies into one single file so that the browser does not have to parse the DOM and then fetch all of the remaining files. 

Finally, I can now feel free to write ES6 since there are now tools like Babel which can compile convenient ES6 code into browser-compatible ES5. 