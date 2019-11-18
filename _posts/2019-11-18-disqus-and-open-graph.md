---
layout: post
title:  "Disqus och Open Graph"
date:   2019-11-18 11.02 +0100
categories: blogg
---

För att implementera en funktion för att kommentera på bloggposterna så har jag använt mig av Disqus (såsom kan ses nedan). 

Open Graph är ett protokoll som gör det enklare för sidor (t.ex. sociala medier) att veta vad din sida handlar om och de kan genom meta-data presentera sidan på ett sätt som är enhetligt och lättöverskådligt för användare. Jag har på denna sida använt mig av title, type, image, url och description.

I och med att Minima använder sig av en [SEO-tag](https://www.rubydoc.info/gems/jekyll-seo-tag/2.2.3) så finns description, title och url redan angivet som meta-taggar i _config.yml och jag behövde därför bara lägga till type och image i head.html. 