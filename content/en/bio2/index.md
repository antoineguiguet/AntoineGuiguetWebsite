---
title: Meet the Team
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Grad Students
        - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      # Show user's social networking links? (true/false)
      show_social: false
      # Show user's interests? (true/false)
      show_interests: true
      # Show user's role?
      show_role: true
      # Show user's organizations/affiliations?
      show_organizations: true
---


---
title: Research
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Research
      text: |-
        The main theme of my research is the **evolution and chemical ecology of plant-insect interactions**. I study the processes by which insects manipulate plant physiology and development, sometimes leading to the formation of structures known as  **galls**. My work on this subject can be grouped into three interdependent lines of research. [<font color="#6fa8dc">The **first axis** involves research into the molecular mechanisms involved in insect gall formation.</font>](#axis-1) [<font color="#e06666">The **second axis** involves studying the evolution of the gall life style and its adaptive consequences in insects.</font>](#axis-2) Finally, [<font color="#93c47d">the **third axis** of my work involves the systematics of the Gracillariidae (Lepidoptera) and Cynipidae (Hymenoptera).</font>](#axis-3)

    design:
      columns: '1'
      spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']

  - block: collection
    id: axis-1
    content: 
      title: <font color="#0b5394">Mechanisms of gall-induction in Hymenoptera</font> 
      subtitle: First axis
      text: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. 
      filters:
        folders:
          - Axe1
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
    # Choose a color such as from https://html-color-codes.info
      background:
      #  color: '#cfe2f3'
       gradient_start: '#cfe2f3'
       gradient_end: '#ffffff'
       gradient_angle: 180
      spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']

  - block: collection
    id: axis-2
    content:
      title: <font color="#990000">Evolution of galling in Hymenoptera</font>
      subtitle: Second axis
      text: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      filters:
        folders:
          - Axe2
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
    # Choose a color such as from https://html-color-codes.info
      background:
      #  color: '#f4cccc'
       gradient_start: '#f4cccc'
       gradient_end: '#ffffff'
       gradient_angle: 180
      spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']

  - block: collection
    id: axis-3
    content:
      title: <font color="#38761d">Systematics and Taxonomy</font>
      subtitle: Third axis
      text: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. 
      filters:
        folders:
          - Axe3
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
    # Choose a color such as from https://html-color-codes.info
      background:
    #  color: '#d9ead3'
       gradient_start: '#d9ead3'
       gradient_end: '#ffffff'
       gradient_angle: 180
      spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '0', '0']
#
#  - block: markdown
#    content:
#      title:
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: wasps.png
#          filters:
#            brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen
---
