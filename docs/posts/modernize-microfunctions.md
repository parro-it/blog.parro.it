# Modernize micro functions

![People Cheering](modernize-microfunctions.jpg)

Something like 23 years ago I was starting to learn
to use and write components using Visual Basic 6.

Since them, I was fascinated by the concept of components,
and so I start to write my collection of libraries.

Soon, I start to be frustrated by the limitations of
the tools I was using.

Maintaining a collection of independent libraries,
and managing dependencies upgrades and compatibility
was a nightmare. The situation slightly improve with Dot.NET,
but still...

It was when I discovered Node.js and NPM that I finally find
I have the right tools to build a really useful collection
of packages.

I wrote [awesome-micro-npm-packages](https://github.com/parro-it/awesome-micro-npm-packages),
a public list where I collect micro-packages built by me or by others
that I use often.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">In principle, I like NPM&#39;s idea of micro-frameworks containing a single class or function, and that should work well with Swift, where …</p>&mdash; Nick Lockwood (@nicklockwood) <a href="https://twitter.com/nicklockwood/status/925738874873184256?ref_src=twsrc%5Etfw">November 1, 2017</a></blockquote>


## The current situation 🤠 🎩 🏭 🏃

🤠 🎩 🏭 🏃

But in 2020, I want to be able to use to use es6 modules
and typescript type descriptions:

```js
import {map} from "map";

console.log(map("ciao", toUpper))
```

So I wrote the first module of the collection:

:thumbsup:

<code data-gist-id="1866f918824936ffb73d8fd0b02879b4"></code>

And here we are

| Name   | Description       |
| ----   | ----------------- |
| map    | map function      |
| filter | filter function   |
| slice  | map function      |





> Photo by Elevate on Unsplash
