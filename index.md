---
layout: article
title: Jake Ward - Python developer
mode: immersive
header:
  theme: dark
article_header:
  type: overlay
  theme: dark
  background_color: '#203028'
  background_image:
    gradient: 'linear-gradient(135deg, rgba(34, 139, 87 , .4), rgba(139, 34, 139, .4))'
    src: /assets/cover.png
---

```python
from jekyll import Blog
from githubpages import hostname, scheme

class Website():
  def __init__(self):
    self.hostname = hostname('gaminggeek.dev') #.dev is the best TLD
    self.scheme = scheme('https')
    self.pages = ['/', '/blog.html', '/commands']
    self.blog = Blog()
```

## Who Am I

Hey, I'm Jake o/ I'm a 17 year old student and Python developer (if you couldn't already tell from the Python snippet above) from Ireland.

## Projects

I've worked on quite a few projects in the past. Here's a few...

Name | Description
-----| ----------
Fire (Active) |  A Discord bot for all! With many features such as music, moderation and even Google Assistant, Fire is the only bot you need. [Website](https://fire.gaminggeek.dev/)
YouTube (Semi-Active) | My YouTube channel consists of a wide variety of content... Just kidding! It's mostly Minecraft (as that's the only game I play) but I'm starting to upload a bit more coding content too [Check it out](https://youtube.com/GamingGeek)
SpectralMC (Gone but not forgotten) | SpectralMC was my Minecraft server I used to work on hoping it would be the **next big thing** but I never really released it. I just had a "beta" period. It was at this time that I used [Skript](https://github.com/SkriptLang/Skript) to "code" plugins
