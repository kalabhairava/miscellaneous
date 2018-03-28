# A Guide to Beginners on Frontend Development

Frontend development has become a complex endeavor in the past few years, which makes it easy to get lost for complete beginners. This guide is by no means exhaustive. It is just intended to give you a direction in which you can begin your journey.

The most challenging thing about Frontend Development is the sheer pace of evolution of so many technologies, all at once. To give you some perspective, When we started building PPT Web Application in 2015, Angular 1 was the latest. Now as I write this in early 2018, Angular 1, 2, and 4 are already a thing of past, Angular 5 is the latest, and Angular 6 is waiting right behind the door. All this happened in just 2-2.5 years. This is just for Angualar, forget so many other SPA frameworks, the evolution of JavaScript as a language, the build tools, asset bundlers, and a ton of other tools you need, just to get started.

Don't be scared.

All that matters is the fundamentals. And fundamentals don't change.

Here is a list of things you need to learn and where to learn them. Internet is full of articles on web development, but most of them are partly good, inaccurate, or absolute crap. You need to make sure you learn from authentic sources to avoid learning bad practices in the beginning. You'd be better off learning good practices from the beginning rather than unlearning bad practices and re-learning good practices later.

## HTML

HTML is the most important and the most ignored part of web development. All of the mainstream browsers are overly forgiving about bad HTML, which makes it easy for developers to get away with bad HTML. 

Although the layout is not affected with bad HTML, it does affect other important things like page rank, and accessibility.

MDN maintains a authentic reference of HTML. [This pathway on MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML) is a good place to start.

Understand what [Semantic HTML](https://en.wikipedia.org/wiki/Semantic_HTML) means. [Use it](https://www.pluralsight.com/guides/html-css/semantic-html) in your code. 

Semantic HTML makes your site more accessible and provides good experience to people with disabilities.

Be empathetic. Write Semantic HTML.

## CSS

CSS is not known as developers' hell for no reason. It can be tricky, but it can also be walk in the park if you know what you're doing. Take some time out to learn the fundamentals of CSS. It'll save you a tonne of time and frustration in future.

Learn about CSS Specificity on [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity) and [CSS Ticks.](https://css-tricks.com/specifics-on-css-specificity/)

Learn all about [CSS Layouts.](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout) Save yourself some existential crisis.

### Less

CSS is not very powerful. It didn't have variables (they were introduced recently) until now or other powerful features like nesting and mixins.

That's where CSS pre-processors like Less and SASS come into play. They provide you these extra features and compile them to native CSS.

[Winless](http://winless.org/online-less-compiler) lets you try out all features of Less. Go ahead and try it.

There are other alternatives like SASS. Explore more.

### Responsive Web Design

Google has a great [beginners guide](https://developers.google.com/web/fundamentals/design-and-ui/responsive/) to responsive web design.

You can read the [original article](http://alistapart.com/article/responsive-web-design) that introduced the idea of responsive web design. It gives you some perspective on how the idea was conceived in the beginning.

#### Bootstrap

Bootstrap is a widely responsive web design framework that we use at Great West. 

There are other alternatives to Bootstrap like Foundation. Feel free to explore more. 

## JavaScript

Understanding JavaScript deeply takes some time and it is tempting to skip learning the language itself and dive directly into frameworks. Don't give in to that temptation and force yourself to learn the language fundamentals. Although it feels like you're wasting time, it'll reward you in the longer run.

1. MDN has a great [introduction to JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript).

2. Douglas Crockford's talks on [JavaScript: The Good Parts](https://app.pluralsight.com/player?name=javascript-good-parts-m0&mode=live&clip=0&course=javascript-good-parts&author=douglas-crockford) explain why JavaScript is a great language.

3. Kyle Simpson's 6 books series [You don't know JS](https://github.com/getify/You-Dont-Know-JS) goes deep into JavaScript. It's little dense for a beginner but you can come back to it later when you have some JavaScript experience.

4. Addy Osmani's [Design Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book/) talks about design patterns in JavaScript.

5. [Closures](http://jibbering.com/faq/notes/closures/) and [Prototypal inheritance](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain) are the two pillars of JavaScript. It might take some time to get your head around it, but once you understand you'll become a better JavaScript developer.

6. More resources [here.](https://github.com/wix/javascript-essentials)

### ES6

ES6 is by far the biggest update to JavaScript.

1. Wes Bos has written a good collection of [articles](https://github.com/wesbos/es6-articles) on ES6. 

2. You can find a deep explanation of ES6 features on the book [Exploring ES6](http://exploringjs.com/es6/index.html) by Dr. Axel. He maitains a newsletter with updates on JavaScript. You can subscribe and keep yourself updated on latest developments in JS. 

## AngularJS

[Yaakov Chaikin's course](https://www.coursera.org/learn/single-page-web-apps-with-angularjs) on AngulraJS is the best I've seen on the framework. He's a funny guy, with a knack for explaining things easily.

He writes about HTML in his [blog.](https://clearlydecoded.com/)

## API

This [article](https://medium.freecodecamp.org/what-is-an-api-in-english-please-b880a3214a82) on medium is a great introduction to APIs.

## package managers

There are two mainstream package managers for NodeJS.

1. npm - Offical package manager. Master the basics with [this course on Udemy.](https://www.udemy.com/npm-mastering-the-basics/)

2. yarn - Node package manager released by Facebook. Master the basics with this [mini course](https://www.youtube.com/watch?v=4MT64gN5dqI) by Andrew Mead.

## Git

Git is a distiributed version control system (VCS). Git is an amazing tool. The more you use it, the more you'll appreciate its clever ways.

[Ry's Git Tutorial](https://www.amazon.com/Rys-Git-Tutorial-Ryan-Hodson-ebook/dp/B00QFIA5OC) is a great book to begin with. It is available for free on Amazon Kindle.

[Pro Git](https://git-scm.com/book/en/v2) is an exhaustive reference, but it's little dense. 

Going through Ry's Git Tutorial should be enough. Read Pro Git if you'd like to delve deep into git.

[Git flow](http://nvie.com/posts/a-successful-git-branching-model/) is widely used branching strategy. A [slightly different version](https://confluence.retirementpartner.com/display/DEV/GIT+Branches+and+merging) of git flow is used at Great West.

[Git tutorials by Atlassian](https://www.atlassian.com/git/tutorials) are very well written. [Read this](https://www.sbf5.com/~cduan/technical/git/) for a wonderful conceptual introduction.

## JSON

JSON is a language independent text format, generally used to exchange data. It is widely used because of its simplicity.

[The official document](http://www.json.org/) is good enough and it takes hardly 30 minutes to go through.

Understand the [difference between a JavaScript object and JSON](https://stackoverflow.com/questions/8294088/javascript-object-vs-json)

## ESLint

[Linting](https://stackoverflow.com/questions/8503559/what-is-linting) is the process of analysing code for potential bugs. 

In its early stages, JavaScript was [designed to be beginner-friendly](https://www.youtube.com/watch?v=hQVTIJBZook) to drive a widespread adoption which makes it prone to errors. Using a linter is important to identify common errors during development stage.

[ESLint](https://eslint.org/docs/user-guide/getting-started) is the linting tool used at Great West. There are other alternatives out there, but this is the best.

Every major editor supports has exensions for ESLint. It's walk in the park installing and configuring ESLint in almost every editor.

[Andrew Mead](https://www.udemy.com/user/andrewmead/) has a great [mini course](https://www.youtube.com/watch?v=nxxl2H_TOTc&list=PLMWjeRChIK6bnp6qaS3rxLGCpc9aQYzEE) on ESLint. It has everything you need to know about ESLint.

## JSDoc

[JSDoc](http://usejsdoc.org/) is a documentation generator for JavaScript, similar to JavaDoc for Java.

It is used at Great West as a format for writing comments to make it easier for other developers reading your code.

## Prettier

Prettier is an opinionated JavaScript formatter that puts an end to millions of man-hours wasted in arguing about formatting styles like spaces vs tabs, right brace style vs left brace style, and other *cough* trivial *cough* style tastes.

Watch [this talk](https://www.youtube.com/watch?v=hkfBvpEfWdA) by James Long, the creator of Prettier.

Prettier plugin is available for all major editors. It doesn't take much time to configure.

Install prettier and don't worry about formatting anymore.

Another advantage is it produces cleaner git diffs, and thereby [easier code reviews.](http://www.sheshbabu.com/posts/speed-up-your-code-reviews-using-eslint-and-prettier/)

## Touch-typing

Go an extra mile and learn touch-typing. I felt a slap on face when I read [this article](http://steve-yegge.blogspot.com/2008/09/programmings-dirtiest-little-secret.html) for the first time. Go ahead and read it. It makes a lot of sense.

Do yourself a favor and learn to touch-type. 

[Keybr](https://www.keybr.com/) and [Keyhero](https://www.keyhero.com/) are pretty great. Klavaro is another great tool. Use keybr until you're comfortable with all the keys, and then use Keyhero to increase your speed. 

Focus on accuracy, speed will follow.

## Some good tech articles

1. [Teach yourself programming in 10 years](http://norvig.com/21-days.html)
2. [A Dao of Web Design](http://alistapart.com/article/dao)
3. [How to search on Google](https://support.google.com/websearch/answer/134479?hl=en)
4. [How the web works](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)
5. [What the heck is a event loop anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ) 

## Blogs

1. [Wes Bos](http://wesbos.com/blog/)
2. [Dr. Alex](http://2ality.com/) - on developments in JS.
3. [David Walsh](https://davidwalsh.name/) - on general web development
4. [Hashnode AMAs](https://hashnode.com/amas) - great way to understand top developers

## Some tips
* Finding smart developers is hard. Finding kind developers is harder. Be a kind developer, help others when they're stuck. Smart and kind developers are endangered species. Strive to be one.
* Be vocal, take credit for your work.
* Be professional. Read [Clean Code](https://www.goodreads.com/book/show/3735293-clean-code) by Robert Martin (Uncle Bob).
* Write comments - help the future you.
* Use descriptive variable names.

## Explore more

1. [Frontend Developer Handbook 2018](https://frontendmasters.com/books/front-end-handbook/2018/)
2. Medium app on Android and iOS
3. [Chrome Devtools](https://github.com/andersoonweb/learning-devtools)
4. [JSConf Videos](https://www.youtube.com/user/jsconfeu/videos?sort=p&shelf_id=2&view=0)
5. [DOM Enlightenment](http://domenlightenment.com/)
6. [Chrome Browser Shortcuts](https://support.google.com/chrome/answer/157179?hl=en)

***P.S:*** Professional software development can be scary in the beginning, but it's also a lot of fun. If you're stuck somewhere or don't know what to do or in existential crisis triggered by a spacing issue, give me a call - +91-7975261158 or drop me an e-mail at manjunathad13@gmail.com. I'm a fairly harmless creature. I won't bite you, mother promise.
