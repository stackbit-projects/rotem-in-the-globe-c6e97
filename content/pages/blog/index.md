---
title: Blog post page
layout: PageLayout
sections:
  - elementId: ''
    variant: variant-b
    colors: colors-a
    title: Latest news
    subtitle: Latest blog posts section example
    actions:
      - type: Button
        label: View All
        altText: View All Posts
        url: /blog
        style: primary
    showRecent: true
    recentCount: 3
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: PostFeedSection
  - type: PostFeedSection
    variant: variant-a
    colors: colors-a
    title: Destinations
    showRecent: false
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    recentCount: 6
---
