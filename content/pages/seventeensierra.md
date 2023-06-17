---
layout: PageLayout
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: Home
sections:
  - type: HeroSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: Forward-Thinking Cybersecurity
    subtitle: 'Pioneering cybersecurity, Empowering Businesses'
    text: >
      At Seventeen Sierra, we excel in providing expert advice and cutting-edge
      cybersecurity solutions. As a beacon of innovative practices, we redefine
      what it means to be secure in today's digital age. We understand your
      desire for excellence, efficiency, and unwavering security. Through our
      unique approach, we can translate your aspirations into reality, helping
      you navigate the cybersecurity landscape with confidence and peace of
      mind. With Seventeen Sierra, you are investing in a future where safety
      meets innovation.
    actions: []
    media:
      type: ImageBlock
      url: /images/e409dc07e5e878329aca93fd4aa1137c.jpg
      altText: Hero image
    backgroundImage: null
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: QuoteSection
    colors: colors-b
    quote: >
      "Everyone hates compliance until they start having to do risk management.
      Compliance is easy compared to having to do critical thinking"
    name: ''
    title: ''
    backgroundImage:
      type: BackgroundImage
      url: /images/OR69HE0.jpg
      backgroundSize: cover
      backgroundPosition: center
      opacity: 70
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-96
          - pb-10
          - pl-4
          - pr-4
        justifyContent: center
      quote:
        textAlign: left
      name:
        textAlign: left
      title:
        textAlign: left
  - type: FeaturedItemsSection
    colors: colors-d
    elementId: ''
    title: Discover Your Cybersecurity Strategy Today
    subtitle: >-
      Empowering businesses through intelligent decision to support their cyber
      mission
    items:
      - type: FeaturedItem
        title: CISO Advisory
        text: >
          This service provides executive-level guidance on shaping and
          executing effective cybersecurity strategies, addressing both tactical
          and strategic security challenges that align with your business
          objectives.
        actions: []
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: IT Security Policy Development
        text: >
          This entails the creation of comprehensive, custom-made security
          policies that define your organization's standards for data
          protection, addressing areas such as access control, incident
          response, and user behavior, ensuring a robust defense against
          potential threats.
        actions: []
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: Risk Mitigation Strategy
        text: >
          This service helps identify potential cybersecurity risks your
          business or products may face and develop tailored strategies to
          mitigate these risks, safeguarding your systems, data, and reputation
          from potential cyber attacks.
        actions: []
        styles:
          self:
            textAlign: left
    actions: []
    columns: 3
    spacingX: 16
    spacingY: 16
    enableHover: false
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: FeaturedPeopleSection
    variant: variant-c
    colors: colors-a
    people:
      - content/data/team/desmond-eagle.json
      - content/data/team/dianne-ameter.json
      - content/data/team/hugh-saturation.json
      - content/data/team/hilary-ouse.json
      - content/data/team/person-frrxp3513.json
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-36
          - pb-72
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
  - type: ContactSection
    colors: colors-d
    title: Get a quote or set up a consultation
    text: >
      Have a question we can answer or a challenge we can help you solve? We’d
      love to connect! Send us a message and we’ll be in touch.
    form:
      type: FormBlock
      elementId: sign-up-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: false
          width: 1/2
        - type: TextFormControl
          name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
        - type: TextFormControl
          name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: full
        - type: CheckboxFormControl
          name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
      submitLabel: Submit form
      styles:
        submitLabel:
          textAlign: center
    media: null
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
---
