---
layout: post
title: Why I started my own <br> programming site
author: Why I started my own programming site
description:
tags: Code, Software Engineer, Deploy, Programming, Blog
image: pic03.jpg
permalink: /:title/
---
<div style="font-size:14px;margin-bottom:20px;"> 15 Sept &#183; 6 min read </div>

Welcome to my site! I'm Alex and I'm from Singapore.

It’s been some time since I’ve thought about starting a programming site. I’ve always questioned the purpose of one, the impact it would bring, or if my efforts would be purely wasteful.
My views changed however, as I saw friends and mentors grow to become better software engineers. This was achieved not just through writing code, contributing to open source projects, or grinding out theoretical knowledge in data structures and algorithms; but in addition, by creating for themselves a platform to explore and explain interesting concepts and ideas learnt.

<h3> Key motivations in starting my programming site</h3>

Besides what was mentioned earlier,  I believe a site like this also:
- Improves reflection and communication through writing and presenting ideas, (which is also a crucial part of the interview process)
- Allows students like myself to showcase our portfolio for potential collaboration,
- Gain a better network in the programming community,
- Get feedback on my journey through sharing it with the wider community.

 With that aim in mind, I decided to build my site on <a href="https://jekyllrb.com/"> Jekyll</a>. This was on the basis of several points:
* Simplicity:  Jekyll does not do any server side processing or have a database, and files are ready to be served. It supports Markdown and Liquid, which is both efficient and easy to implement, and stitches the content and templates together to produce a static website. It is great to work with once you understand its basic structure and functions
* Speed: Less requests as pages are pre-rendered html pages
* Blog aware: Optimized for posts, pages and custom layouts, and designed for building personal portfolio websites. Jekyll also allows content migration from popular platforms like Wordpress

<h3> Deploying my site </h3>

On this occasion, I utilised AWS S3 for file storage and CloudFlare as a CDN service. This takes care of TLS/SSL Server Certificate, DNS, Caching and DDoS Protection. (update: removed CloudFlare and transitioning to Cloudfront)
As I start expanding the reach of my blog I intend to improve on the site to make it more powerful, fast and <b><i>extensible.</i></b>
- Implement CI/CD practices: Configure bitbucket pipelines to deploy to staging and production environments. From there I will continue to use the s3_website module to push the contents up to S3 buckets
- Speed up the blog to improve User Experience


<h3> Foreseen Challenges </h3>

Starting my own site may seem exciting at first, with numerous ideas to make the site better. As time passes, and school, work, internships and projects take precedence, I expect it to get increasingly harder to continuously generate new content and stay motivated in jotting down thoughts on a public platform like this one. I’ve identified 3 reminders for myself:

<blockquote> 1. Building a product like your own site should be an iterative process </blockquote>
This is something that should be familiar with us Software Engineers. When we write code, we do it with the intention of improving a particular product or process, step by step. Similarly, when developing your own site, you shouldn’t rush to achieve the grand plans we had in mind. Challenges and road blocks can and will come along the way, and instead, you should work towards a minimum viable product and iterate on it to get to where you want.


<blockquote> 2. It shouldn’t be perfect </blockquote>
Personally this is something I find quite challenging to grasp. As someone who’s extremely meticulous in my work and pays crazy attention to detail, being content with how a certain blog post looks or page is written would be really hard- especially when it's in the public eye. Nonetheless, being more ignorant to the little errors in your writing will actually allow yourself to become better over time. Like any other discipline, good writing takes practice, and you are bound to improve progressively. So start brushing off those minuscule errors, stop rephrasing your sentences and instead, enjoy the process of sharing your ideas with other like-minded individuals.


<blockquote> 3. While programming is technical in nature, the site can showcase your personality </blockquote>
Make it fun! The key advantage of having your own site is so that you can design, craft and mould it in any way you like, on your own schedule. Draw inspiration from your experiences, the little conversations you have along the way, and the things you see in your daily lives. While websites should be highly functional, this one can also be a form of your own self-expression.


Thanks for tuning in to this post!

<span class="badge badge-secondary">Code</span>
<span class="badge badge-secondary">Software Engineering</span>
<span class="badge badge-secondary">Blog</span>
