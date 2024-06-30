---
title: My page
type: landing

sections:
  - block: portfolio
    id: projects
    content:
      title: My Blogs
    #   subtitle: My subtitle
      text: |2-
        You can find all my blog posts here.

        My blog posts cover a wide range of topics. Click the button below and you can find them in corresponding categorizes.

        I do not have a specific oriented group of readers (as it should be, since the topic range is wide). But each post may have its designed reader group.
        For example, some research-related posts may not be friendly to non-professionals.
        <br/><br/>
      filters:
        # Folders to display content from
        folders:
          - post
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      buttons:
        - name: All
          tag: '*'
        - name: Research
          tag: research
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: 3
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
