---
title: Academic Research Lab Homepage
summary: "Homepage for an academic research lab featuring lab overview, team, projects, publications, news, and join us sections."
date: 2026-07-22
type: landing
sections:
  - block: hero
    content:
        title: Welcome to the Advanced Research Lab
        text: Pushing the boundaries of science through interdisciplinary research and collaboration.
        primary_action:
          text: Join Our Lab
          url: "#join-us"
          icon: hero/user-add
          style: gradient
        secondary_action:
          text: Meet the Team
          url: "#team"
          icon: hero/users
          style: outline
    design:
        background:
          color:
            light: "#e0f2fe"
            dark: "#1e3a8a"
        spacing:
          padding:
            - 4rem
            - 0
            - 4rem
            - 0
    id: lab-overview
  - block: team-showcase
    content:
        title: Our Team
        people:
          - name: Dr. Alice Smith
            role: Principal Investigator
            bio: Expert in artificial intelligence and computational models.
            image: team/pi-alice-smith.jpg
          - name: Dr. Bob Johnson
            role: Senior Researcher
            bio: Specialist in machine learning and data science.
            image: team/bob-johnson.jpg
          - name: Clara Lee
            role: Postdoctoral Fellow
            bio: Focused on natural language processing.
            image: team/clara-lee.jpg
          - name: David Kim
            role: PhD Candidate
            bio: Researching deep learning applications.
            image: team/david-kim.jpg
    id: team
  - block: portfolio
    content:
        title: Projects
        items:
          - title: Project Alpha
            summary: Exploring AI-driven healthcare solutions.
            image: projects/alpha.jpg
            url: /projects/project-alpha/
          - title: Project Beta
            summary: Developing sustainable energy technologies.
            image: projects/beta.jpg
            url: /projects/project-beta/
          - title: Project Gamma
            summary: Innovations in robotics and automation.
            image: projects/gamma.jpg
            url: /projects/project-gamma/
    id: projects
  - block: collection
    content:
        title: Recent Publications
        kind: publication
        limit: 3
        link_more_text: See all publications
        link_more_url: /publications/
        sort_by: date
    id: publications
  - block: collection
    content:
        title: "News & Updates"
        kind: blog-post
        limit: 3
        link_more_text: Read all news
        link_more_url: /news/
        sort_by: date
    id: news
  - block: cta-card
    content:
        title: Join Our Lab
        text: "We're looking for talented researchers and collaborators. Apply now to be a part of groundbreaking research."
        button:
          text: Apply Now
          url: /join-us/
          icon: hero/academic-cap
    id: join-us
---
