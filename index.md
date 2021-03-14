---
layout: article
title: Void- Just another person on the internet.
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
from jekyll import Blog  # yes i am aware jekyll is not python but shush
from github import Pages
from site.pages, import root, commands
from site.utils import redirect

pages = Pages()

class Website():
  def __init__(self):
    self.hostname = 'gaminggeek.dev' #.dev is the best TLD
    self.protocol = 'https'
    self.blog = Blog()
    self.pages = pages

  @pages('/')
  def rootpage(self):
    return root

  @pages('/blog')
  def blogpage(self):
    return self.blog

  @pages('/commands')
  def cmdspage(self):
    return redirect('https://fire.gaminggeek.dev/commands')
```

## Who Am I

Hey, I'm Void, just another person on the internet
## Projects

I don't have very many projects, however heres a few.

Name | Description
-----| ----------
Placeholder |  Placeholder Description [Website](LINK)
