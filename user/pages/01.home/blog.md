---
title: Home
blog_url: Home

sitemap:
    changefreq: weekly
    priority: 1.03

modular_content:
    items: @self.modular

content:
  items: @self.children
  order:
        by: date
        dir: desc
  limit: 8
  pagination: true


feed:
    description: CMPT-363-153 Course Companion
    order:
      by: date
      dir: desc

pagination: true
---
