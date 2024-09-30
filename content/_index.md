---
title: 'Home'
date: 2023-10-24
type: landing
sections:

# Page sections

  - block: hero
    content:
      title: Hugo Blox
      text: Build your site with blocks 🧱
      primary_action:
        text: Get Started
        url: https://example.com
        icon: sparkles
      secondary_action:
        text: Read the docs
        url: https://example.com
      announcement:
        text: Announcing the release of version 1.
        link:
          text: Read more
          url: https://example.com

  - block: resume-biography-2
    content:
      title: Zoe Southcott, Psychotheraputic Counsellor
      # Note: `username` refers to the user's folder name in `content/authors/`
      image: newlogo
      username: admin
    design:
      spacing:
        padding: [0, 0, 0, 0]

  - block: collection
    content:
      filters:
        folders:
          - post
      count: 25
    design:
      view: article-grid
---
