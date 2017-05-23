---
layout: post
title:  "Don't call yourself a good web developer if you don't know Dependency Management."
date:   2017-05-22 05:11:03
categories: Work
postUrl: Dont_call_yourself_a_good_web_developer_if_you_dont_know_Dependency_Management
bannerImg: jekyllwithgulp.jpg
comments: true
---
 

Dependencies are a cornerstone of modern web development. These are the required tools, plugins, libraries and frameworks necessary to build high-level web applications.

The sheer number of dependencies has skyrocketed in the last few years. Over time developers have adopted dependency management tools which alleviate the stress of keeping dependencies organized and up-to-date. These tools lead to an optimized workflow for developers and project managers.

I’ve cataloged the best dependency tools here including both well-established and newly-emerging platforms. Professional web development requires continuous learning and I’d argue dependency management is a skillset worth learning.

## 1.NPM

I couldn’t write this guide without giving credit to the Node Package Manager. Built on Node.js, this system powers a tremendous repository of 100,000+ packages and modules.

npm js library
Each project can use a package.json file setup through NPM and even managed with Gulp(on Node). Dependencies can be updated and optimized right from the terminal. And you can build new projects with dependency files and version numbers automatically pulled from the package.json file.

NPM is valuable for more than just dependency management, and it’s practically a must-know tool for modern web development. If you’re confused please check out this Reddit thread for a beginner’s explanation.

## 2. Bower
The package management system Bower runs on NPM which seems a little redundant but there is a difference between the two, notably that NPM offers more features while Bower aims for a reduction in filesize and load times for frontend dependencies.

Check out this Stack question to learn more about the subtle differences.

bower package manager
Some devs argue that Bower is basically obsolete since it runs on NPM, a service that can do almost everything Bower can do. Generally speaking this isn’t wrong.

But devs should realize Bower can optimize the workflow specifically with frontend dependencies. I recommend Ben McCormick’s article Is Bower Useful to learn more about the value offered from both package management tools.

## 3. RubyGems
RubyGems is a package manager for Ruby with a high popularity among web developers. The project is open source and inclusive of all free Ruby gems.

To give a brief overview for beginners, a “gem” is just some code that runs on a Ruby environment. This can lead to programs like Bundler which manage gem versions and keep everything updated.

rubygems website gems management
Rails developers will love this feature, but what about frontend packages? Since Ruby is open source, developers can build projects like Bower for Rails. This brings frontend package management to the Ruby platform with a small learning curve.
 
## 4. RequireJS
There’s something special about RequireJS in that it’s primarily a JS toolset. It can be used for loading JS modules quickly including Node modules.

RequireJS can automatically detect required dependencies based on what you’re using so this might be akin to classic software programming in C/C++ where libraries are included with further libraries.

requirejs webapp
You’ll find an interesting GitHub discussion on this topic and the value it offers modern web developers. Granted other JS management tools like webpack have popped up, RequireJS still works in production environments. And if it works for you that’s all that matters.

## 5. Jam
Browser-based package management comes in a new form with JamJS. This is a JavaScript package manager with automatic management similar to RequireJS.

All your dependencies are pulled into a single JS file which lets you add and remove items quickly. Plus these can be updated in the browser regardless of other tools you’re using (like RequireJS).

jamjs website
Libraries are updated based on the latest versions through the terminal. Each project can be created automatically with optimized components based on your needs. Jam is free on GitHub and worth a look if you have the time.

## 6. Browserify
Most developers know of Browserify even if it’s not part of their typical workflow. This is another dependency management tool which optimizes required modules and libraries by bundling them together.

These bundles are supported in the browser which means you can include and merge modules with plain JavaScript. All you need is NPM to get started and then Browserify to get moving.

Check out this intro tutorial to see how Node can be managed right in the browser. There’s also a lengthy Browserify handbook hosted on GitHub for free. The idea is to bring all these Node tools into the browser and save time by automating the process with Browserify.

## 7. Mantri
Still in its early stages of growth, MantriJS is a dependency system for mid-to-high level web applications. Dependencies are managed through namespaces and organized functionally to avoid collisions and reduce clutter.

mantri js dependency manager
Mantri is currently at v0.2.2 at the time of writing. It’s completely open source and built for more complex web applications that require large bundles of dependencies. Mantri aims to follow modular programming practices and hopes to encourage developers onto the same path.

## 8. Volo
The project management tool volo is an open source NPM repo that can create projects, add libraries, and automate workflows.

Volo runs inside Node and relies on JavaScript for project management. A brief intro guide can be found on GitHub explaining the installation process and common usage. For example if you run the command volo create you can affix any library like HTML5 Boilerplate.

volo js website
But aside from creating new projects you can also add/update libraries for older projects. Volo ties into everything you would need for frontend development. Check out volo’s design goals to see how it operates in a real-world project.

## 9. Ender
Ender is the “no-library library” and is one of the lightest package managers you’ll find online. It allows devs to search through JS packages and install/compile them right from the command line. Ender is thought of as “NPM’s little sister” by the dev team.

ender js illustration website
Naturally the whole Ender framework is available for free on GitHub. It’s simply a tool that you install to help manage consumption of frontend JavaScript frameworks for local projects. Everything is meant to run with ease to the fullest potential for a frontend developer’s workflow.

The main Ender website has quality documentation so it’s worth a glance if you’re interested.

## 10. pip
The recommended method for installing Python dependencies is through pip. This tool was created by the Python Packaging Authority and it’s completely open source just like Python itself.

pip python package manager
The majority of Python developers recommend pip for dependencies including the Django team. Whether you’re just getting started with Python or already use it consistently with backend development, this is a package manager you’ll be glad to have in your toolbox.

## 11. Composer
Composer is a package manager very similar to NPM, but it’s focused solely on PHP libraries. You can find a list of dependencies on Packagist which includes large PHP frameworks such as Laravel.

If you’re a PHP developer of any kind I seriously recommend looking into Composer. It’s easy to get started but difficult to fit into your workflow. However with practice it’ll become a staple for PHP dev projects.

composer php dependency manager
This is a versatile tool with the potential to grow even larger in time. Plus NPM can mix with Composer to create a frontend + backend dependency management system for all your PHP/JS projects.

Wrapping Up
It’s clear many of these dependency managers have similar traits with similar qualities. Some are built to solve alternate problems and can even run in tandem with each other (ie. Composer and NPM).

The subject of dependency management can be tough for new developers. I recommend picking one of these tools and researching in-depth to learn as much as possible. Try building small webapps and learn why dependency management is useful.

Once you learn how to apply these tools into your workflow you’ll never consider going back.


<!--![Image of Yaktocat](https://cdn-images-1.medium.com/max/1100/1*BhKLerYwVqd5j1ijfLgB_g.jpeg)-->

<!--
>After installation of gulp you need to download a “jekyll-gulp-sass-browser-sync” package from this github repo :
[https://github.com/shakyShane/jekyll-gulp-sass-browser-sync][repo-url]
<br><br>
clone this repo: type this command to your bash
git clone [https://github.com/shakyShane/jekyll-gulp-sass-browser-sync.git][none]-->


<!-- 
Jekyll also offers powerful support for code snippets:

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh]. -->

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
[css-tricks]: https://css-tricks.com/gulp-for-beginners/ 
[repo-url]: https://github.com/shakyShane/jekyll-gulp-sass-browser-sync
[none]: javascript:void(0)