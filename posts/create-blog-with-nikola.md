<!--
.. title: Create a blog site with Nikola, gitnub, and Netlify
.. slug: create-blog-with-nikola
.. date: 2020-11-30 18:28:40 UTC
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

The first thing I need to do to start making blogs is finding a platform for my blogs. Since my needs are simple, 
I don't want a full fledged CMS like Wordpress or Joomla. A static webpage generator should work fine for my 
purpose. Preferrably it should use a program language I am familiar with, like Python or JS, so I can tinker it 
if I want/need to.

Nikola seems to be the one fits the bill.

## Brief introduction to Nikola

[Nikola](http://getnikola.com) is an open source Statis Site Generator. It generates static web pages from 
multiple input formats (`reStruturedText`, `Markdown`, `Jupyter Notebook`, `HTML`, and have plugins for many 
other formats. The generated static web pages and be hosted anywhere, the platform is batteries included and 
easily extensible. 

## Clone Nikola blog-template

Nikola offers many featues. We are interested in its blog-template today. To create you own blog template, you 
should fork the Nikola blog-template from github: [Nikola blog-template](http://github.com/getnikola/blog-template). 

## Build Nikola blog with Netlify

[Netlify](https://www.netlify.com/) is "The fastest way to build fastest website". You can connect you github repository 
to Netlify and publish the website. Nikola blog-template provides a shortcut to simply the process. Just click ![alt text](https://camo.githubusercontent.com/417d890ba67c98ad5856b715343a61cdbf07d72b9bd5b79dd45d43de634c29ea/68747470733a2f2f7777772e6e65746c6966792e636f6d2f696d672f6465706c6f792f627574746f6e2e737667) and follow the instruction.

## Configure Netlify

TBD

Enjoy your new blog site hosted by Netlify!
