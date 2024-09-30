---
title: 'Home'
date: 2023-10-24
type: landing
sections:

# Page sections

  - block: hero
    content:
      title: Southcott Psychotherapy
       text: 'Counselling : I practise using a Person Centred Approach and a blend of Dialectical Behaviour Therapy, Positive Psychology, and Mindfulness. My Masters degree training and work experience enables me to practise as an integrative counsellor, utilising a range of therapeutic approaches depending on your needs and goals. I specialise in working with those experiencing addiction - both substance and process, disordered eating, and trauma. Supervision: A positive, creative, reinforcing supervision style, We can collaboratively work toward growth and development, valuing openness, individuality, and learning.'
      primary_action:
        text: Contact
        url: /contact
        icon: sparkles
      secondary_action:
        text: Read More
        url: /about
      #announcement:
       # text: Announcing the release of version 1.
       # link:
        #  text: Read more
       #   url: https://example.com

    design:
      background:
        image:
      # Name of image in `assets/media/`.
          filename: background.jpg
      # Apply image filters?
          filters:
        # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0.8
      #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
      # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
      # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
      # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true

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
      title: Blog
      filters:
        folders:
          - post
      count: 25
    design:
      view: article-grid
---
