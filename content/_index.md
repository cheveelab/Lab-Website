---
title: Academic Research Lab Homepage
summary: "Research lab focusing on interdisciplinary excellence."
date: 2024-03-20
type: landing
sections:
  - block: hero
    content:
      title: Welcome to the [Lab Name]
      text: Pushing the boundaries of science through interdisciplinary research and collaboration.
      primary_action:
        text: Join Our Lab
        url: "/join-us"
        icon: user-plus
        style: gradient
      secondary_action:
        text: Meet the Team
        url: "/team"
        icon: hero/users
        style: outline
    design:
      background:
        color:
          light: "#e0f2fe"
          dark: "#1e3a8a"
    id: lab-overview
  - block: team-showcase
    content:
      title: Our Team
      people:
        - name: Dr. PI Name
          role: Principal Investigator
          bio: Expert in your field.
          image: team/pi.jpg
        - name: Researcher 1
          role: Postdoctoral Fellow
          bio: Specializing in X.
          image: team/member1.jpg
    id: team
  - block: portfolio
    content:
      title: Research Projects
      items:
        - title: Project Alpha
          summary: Exploring new frontiers in X.
          image: projects/Traces.png
          url: /project/project-alpha/
        - title: Project Beta
          summary: Developing technologies for Y.
          image: projects/beta.jpg
          url: /project/project-beta/
    id: projects
  - block: markdown
    id: publications
    content:
      title: Recent Publications
      text: |
        {{< list_publications limit=3 >}}
      link_more_text: "See more publications"
      link_more_url: "/publication/"
    design:
      columns: '1'
      spacing:
        padding: ['4rem', '0', '4rem', '0']
  - block: collection
    content:
      title: News & Updates
      count: 3
      filters:
        folders:
          - post
    design:
      view: card
    id: news
  - block: cta-card
    content:
      title: Join Our Lab
      text: "We're looking for talented researchers. Apply now."
      button:
        text: Apply Now
        url: /join-us/
        icon: hero/academic-cap
    id: join-us
---
