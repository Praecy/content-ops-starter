---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Welcome to my Portfolio Website
      color: text-dark
      type: TitleBlock
      styles:
        self:
          textAlign: left
          fontWeight: 400
    subtitle: I am Prashanth Yadamala
    text: >
      As a dedicated and detail-oriented Data Analyst, I am passionate about
      using the power of data to help solve problems faced by people and
      businesses. 


      Proficient in Power BI, SQL, Excel, Python and R, I thrive in converting
      complex raw data to simple yet informative visuals and actionable
      recommendations to assist in the decision-making process. 
    actions:
      - label: Check out some of my projects
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/Profile_Picture.jpg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
      styles:
        self:
          padding:
            - pl-40
            - pr-40
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
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
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
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
