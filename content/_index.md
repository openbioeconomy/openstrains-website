---
title: Open Strain Engineering Consortium 
summary: Landing page for an academic consortium showcasing tools and team members.
date: 2026-05-22
design:
  spacing: 6rem
type: landing
sections:
  - block: hero
    content:
        title: Empowering Collaborative Academic Research
        text: Uniting researchers worldwide with a portfolio of cutting-edge tools for impactful innovation.
        primary_action:
          text: Explore Our Tools
          url: "#tools"
        secondary_action:
          text: Meet the Team
          url: "#team"
    design:
        background:
          gradient:
            start: primary-600
            end: secondary-600
            direction: 135
          text_color_light: true
    id: intro
  - block: collection
    content:
        title: Our Portfolio of Research Tools
        text: "Explore the tools we develop and maintain, designed to accelerate academic discovery."
        count: 6
        page_type: project
        sort_by: Date
        sort_ascending: false
    design:
        view: card
        columns: 3
        fill_image: true
        show_date: true
        show_read_more: true
    id: tools
  - block: team-showcase
    content:
        title: Meet Our Consortium Team
        subtitle: "Researchers & Engineers"
        text: Our diverse team drives research excellence and innovation across disciplines.
        user_groups:
          - Principal Investigators
          - Research Engineers
          - PhD Students
        sort_by: name_family
        sort_ascending: true
        cta:
          text: Join Our Consortium
          url: /join
    design:
        show_role: true
        show_organizations: true
        show_social: true
        max_interests: 3
        align: left
        max_columns: 3
    id: team
---
