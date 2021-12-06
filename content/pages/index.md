---
title: Home
layout: PageLayout
sections:
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-a
    title: Welcome to Rotem in the Globe
    text: "Thanks for stopping by! Here you can find all the recent and cool places I've traveled in the past years Have fun \U0001F30F\n"
    actions:
      - type: Button
        label: Subscribe
        url: 'https://www.stackbit.com/'
        style: primary
        elementId: hero-main-button
    media:
      type: ImageBlock
      url: /images/Rotem thai 1.png
      altText: Image alt text
      caption: Image caption
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-11
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-16
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - colors: colors-e
    elementId: ''
    title: My journey so far
    items:
      - elementId: ''
        title: Continents
        subtitle: ''
        text: |
          # 5
        author: ''
        rating: 1
        isRatingVisible: false
        featuredImage:
          type: ImageBlock
          url: /images/Frame 10-132203ca.png
          altText: Item image
        actions: []
        styles:
          title:
            textAlign: left
          subtitle:
            fontWeight: 400
            fontStyle: normal
            textAlign: left
          text:
            textAlign: left
          actions:
            justifyContent: flex-start
      - type: FeaturedItem
        title: Countries
        featuredImage:
          url: /images/Frame 11-d699e598.png
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          title:
            textAlign: center
          text:
            textAlign: center
        text: |
          # 32
      - type: FeaturedItem
        title: Near death exp
        text: |
          # 2
        featuredImage:
          url: /images/Frame 12-2c079d1c.png
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          title:
            textAlign: center
          text:
            textAlign: center
    columns: 3
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-20
          - mb-20
          - ml-20
          - mr-20
        padding:
          - pt-20
          - pb-20
          - pl-20
          - pr-20
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: double
        borderColor: border-primary
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: flex-start
    type: FeaturedItemsSection
  - elementId: ''
    variant: variant-a
    colors: colors-h
    title: Recent places in the globe
    actions:
      - type: Button
        label: View All
        altText: View All Posts
        url: /blog
        style: primary
        showIcon: false
    posts:
      - content/pages/blog/post-one.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-three.md
    showDate: false
    showAuthor: false
    styles:
      self:
        height: auto
        width: full
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-20
          - pb-20
          - pl-20
          - pr-20
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedPostsSection
  - elementId: ''
    colors: colors-i
    quote: |
      ## “Travel is the only thing you buy that makes you richer"
    name: Unkown
    backgroundImage:
      url: /images/Frame 6.jpg
      altText: Product Marketing Manager Quote
      styles:
        self:
          opacity: 100
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-24
          - mb-24
          - ml-24
          - mr-24
        padding:
          - pt-32
          - pb-32
          - pl-4
          - pr-4
        justifyContent: center
      quote:
        textAlign: left
      name:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
      title:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
    type: QuoteSection
  - elementId: ''
    colors: colors-a
    title: Did you know?
    text: |
      On my free time, I practise some Acro yoga with my partner
    media:
      type: ImageBlock
      url: /images/Mask Group-6dfa3a39.jpg
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-28
          - pb-14
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - elementId: ''
    colors: colors-a
    title: Small tip
    text: >
      No matter where you go, it's always a good idea to take a music instrument
      with you :)
    media:
      type: ImageBlock
      url: /images/midburn2.jpg
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-14
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderColor: border-primary
        borderWidth: 0
        borderStyle: solid
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: ContactSection
    colors: colors-f
    title: Want to be part of my next destination?
    text: |
      Subscribe to my blog and see all updates before everyone! 
    form:
      type: FormBlock
      elementId: contact-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: email
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
      submitLabel: Subscribe
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-36
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      text:
        textAlign: left
---
