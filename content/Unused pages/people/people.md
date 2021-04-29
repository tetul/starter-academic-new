---
# An instance of the People widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: false

# Order that this section appears on the page.
weight: 10

title: People
subtitle: Current and past members

content:
  # Choose which groups/teams of users to display.
  #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
  user_groups:
  - Principal Investigators
  - Researchers
  - Grad Students
  - Administration
  - Visitors
  - Alumni

  # Page type to display. E.g. project.
  page_type: team

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0


design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false

  show_interests: false
  show_role: true
  show_social: true
    
---
