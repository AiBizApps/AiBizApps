---
type: PageLayout
title: 'MS Dynamics365 CRM Partner 가온아이입니다. '
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Microsoft Dynamics 365가 지원하는 인텔리전트 비즈니스 어플리케이션
    subtitle: >-
      Microsoft Dynamics 365가 지원하는 인텔리전트 마케팅 – AI 기반 마케팅으로 성장을 가속화하세요. 고객과의 시간을
      확보하는 것이 곧 영업의 핵심입니다. CRM을 단순한 영업 관리 도구를 넘어, AI 기반의 영업 파트너로 전환하세요. 영업팀이 판매
      과정을 주도하고, 수익 창출 속도를 높이며, 지속 가능한 성장을 달성할 수 있도록 지원합니다.
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
        flexDirection: row-reverse
        textAlign: left
    type: HeroSection
    actions: []
  - type: FeaturedItemsSection
    title: Value propositions
    items:
      - type: FeaturedItem
        title: 자동화와 인사이트로 영업 생산성을 향상 시키세요.
        subtitle: 영업사원에게 더 많은 시간을 준다면 무엇을 할 수 있을까요?
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        featuredImage:
          type: ImageBlock
          url: /images/그림2.png
          altText: Item image
          caption: Caption of the image
          elementId: ''
        actions:
          - type: Button
            label: ''
            altText: ''
            url: /
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: 영업 성과와 수익 성장을 견인하세요
        subtitle: ''
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        featuredImage:
          type: ImageBlock
          url: /images/그림7.png
          altText: Item image
          caption: Caption of the image
          elementId: ''
        actions:
          - type: Button
            label: ''
            altText: ''
            url: /
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: I'm Focused
        subtitle: ''
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        featuredImage:
          type: ImageBlock
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: Item image
          caption: Caption of the image
          elementId: ''
        actions:
          - type: Button
            label: ''
            altText: ''
            url: /
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        elementId: ''
        styles:
          self:
            textAlign: left
    actions: []
    colors: colors-f
    columns: 1
    spacingX: 16
    spacingY: 16
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        textAlign: left
    subtitle: 영업팀이 고객에게 집중할 수 있는 환경을 제공합니다.
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
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    subtitle: Projects
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        textAlign: left
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: false
          placeholder: Your name
          width: 1/2
          isRequired: true
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: false
          placeholder: Your email
          width: 1/2
          isRequired: true
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: false
          placeholder: Type your message here
          width: full
          isRequired: false
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
          isRequired: false
      submitLabel: Send Message
      elementId: contact-form
      styles:
        self:
          textAlign: left
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
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---
