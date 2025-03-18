---
title: Home
slug: /
sections:
  - type: FeaturedItemsSection
    title:
      text: High-End Window and Solar panel cleaning
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Call (503)- 606 - 6201
    items:
      - type: FeaturedItem
        title: Commercial Cleaning
        subtitle: $14.99/Window
        image:
          type: ImageBlock
          url: /images/highendwindows.jpg
          altText: Faux Fur Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
            textAlign: left
            borderRadius: none
            flexDirection: col
            justifyContent: center
      - type: FeaturedItem
        title: Solar Panel
        subtitle: $16.99/Panel
        image:
          type: ImageBlock
          url: /images/solar panel.webp
          altText: Faux Fur Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
            textAlign: left
            borderRadius: none
            flexDirection: col
            justifyContent: center
      - type: FeaturedItem
        title: High-End Residential Windows
        subtitle: $12.99/ Window
        image:
          type: ImageBlock
          url: /images/Normalwindow.jpeg
          altText: Faux Fur Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
            textAlign: left
            borderRadius: none
            flexDirection: col
            justifyContent: center
    actions:
      - label: Book a Free Estimate Today!
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
    badge:
      label: Licensed and Bonded!
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
        fontWeight: 500
  - type: GenericSection
    title:
      text: 100% guarentee to bring back the shine
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      After each session, we will walk through the property with you to showcase
      the quality of our work.


      Any remaining spots will be promptly addressed.


      Additionally, we offer a free 1 week warranty! Yes, free Warranty!
    actions:
      - label: Call us (503)-606-6201
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
    media:
      url: /images/Adobe Express - file.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: Our promise
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-3.md
      - content/pages/blog/case-study-2.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Free Estimates today
      color: text-dark
      type: TitleBlock
    subtitle: Quick and Hassle Free estimate by our Experts
    text: ''
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your phone number
          isRequired: true
          width: full
          type: EmailFormControl
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your zipcode
          isRequired: true
          width: full
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit or Call (503)-606-6201
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  type: Seo
type: PageLayout
---
