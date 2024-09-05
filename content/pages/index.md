---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      I’m a Software Engineer, 3D Artist,Computer Science Student, and a game
      developer.
    subtitle: >-
      I’m balancing school with my passion projects, including a game I'm
      developing in my spare time. I have other projects I'm working on too. Be
      sure to stay tuned as I'm going to be updating as I complete my journey!
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
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
        fontStyle: italic
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    media:
      type: VideoBlock
      title: MyGameAnd Models
      url: ''
      elementId: ''
      autoplay: false
      loop: false
      muted: false
      controls: true
      aspectRatio: '16:9'
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
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
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
---
