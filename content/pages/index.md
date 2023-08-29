---
layout: PageLayout
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: Seventeen Sierra
sections:
  - colors: colors-d
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
      url: /images/e409dc07e5e878329aca93fd4aa1137c.jpg
      altText: Hero image
      type: ImageBlock
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
    type: HeroSection
  - colors: colors-b
    quote: >
      "Everyone hates compliance until they start having to do risk management.
      Compliance is easy compared to having to do critical thinking."
    name: ''
    title: ''
    backgroundImage:
      url: /images/OR69HE0.jpg
      backgroundSize: cover
      backgroundPosition: center
      opacity: 70
      type: BackgroundImage
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
    type: QuoteSection
  - colors: colors-d
    elementId: ''
    title: Discover Your Cybersecurity Strategy Today
    subtitle: >-
      Empowering businesses through intelligent decision to support their cyber
      mission
    items:
      - title: CISO Advisory
        text: >
          This service provides executive-level guidance on shaping and
          executing effective cybersecurity strategies, addressing both tactical
          and strategic security challenges that align with your business
          objectives.
        actions: []
        styles:
          self:
            textAlign: left
        type: FeaturedItem
      - title: IT Security Policy Development
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
        type: FeaturedItem
      - title: Risk Mitigation Strategy
        text: >
          This service helps identify potential cybersecurity risks your
          business or products may face and develop tailored strategies to
          mitigate these risks, safeguarding your systems, data, and reputation
          from potential cyber attacks.
        actions: []
        styles:
          self:
            textAlign: left
        type: FeaturedItem
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
    type: FeaturedItemsSection
  - colors: colors-a
    variant: variant-c
    actions: []
    people:
      - null
      - null
      - null
      - null
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
    type: FeaturedPeopleSection
  - type: ContactSection
    colors: colors-d
    backgroundSize: full
    title: Contact us
    text: We look forward to hearing from you.
    form:
      type: FormBlock
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: name
          placeholder: Your name
          isRequired: 'true'
          width: 1/2
        - type: EmailFormControl
          name: email
          placeholder: Your email
          isRequired: 'true'
          width: 1/2
        - type: TextFormControl
          name: address
          placeholder: Your home address
          isRequired: 'false'
          width: full
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          isRequired: 'false'
          width: full
      submitLabel: Send Message
    media: null
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
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
