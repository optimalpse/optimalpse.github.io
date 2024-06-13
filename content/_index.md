<!-- ---
title: Homepage
type: landing

sections:
  - block: collection
    id: posts
    content:
      title:
      subtitle: ''
      text:
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - post
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: compact
--- -->
---
title: "Welcome to Our Website"
date: 2023-06-13
draft: false
---

## About Us

![Group Photo 1](/images/group-photo-1.jpeg)
![Group Photo 2](/images/group-photo-2.jpeg)

We are a team of passionate individuals dedicated to [...]. Our mission is to [...].

[Add more content about your team or organization]

## Latest Posts

{{ range first 5 (where .Site.RegularPages "Section" "posts") }}
- [{{ .Title }}]({{ .RelPermalink }})
{{ end }}