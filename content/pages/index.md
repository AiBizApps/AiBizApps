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
    title: Ai BizApps
    subtitle: 'Microsoft Dynamics 365가 지원하는 인텔리전트 마케팅 – AI 기반 마케팅으로 성장을 가속화하세요. '
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
  - type: TextSection
    title: Microsoft Dynamics 365가 지원하는 인텔리전트 비즈니스 어플리케이션
    text: >-
      Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
      Sed ut perspiciatis undeomnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
    colors: colors-f
    variant: variant-a
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        textAlign: left
    subtitle: >-
      AI 기반 영업으로 수익 성장을 이끌어보세요. 고객과의 시간을 확보하는 것이 곧 영업의 핵심입니다. CRM을 단순한 영업 관리 도구를
      넘어, AI 기반의 영업 파트너로 전환하세요. 영업팀이 판매 과정을 주도하고, 수익 창출 속도를 높이며, 지속 가능한 성장을 달성할
      수 있도록 지원합니다. AI는 영업사원에게 다음 행동에 대한 추천, 성사 가능성이 높은 기회 인사이트, 자동화된 프로세스를 제공하여
      영업 역량을 한층 끌어올립니다. KAONI 는 전략, 실전 경험, 변화관리 서비스를 통해 영업 성공을 지원합니다. 또한
      Dynamics 365 는  Microsoft 365 및 Power Platform 과의 통합 모델을 통해 플랫폼과 애플리케이션을
      안정적으로 운영하며, 기업이 새로운 기능을 빠르게 활용하고 IT 효율성을 확보하여 경쟁력을 강화할 수 있도록 도와드립니다.
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
