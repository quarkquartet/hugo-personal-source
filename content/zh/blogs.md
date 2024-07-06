---
title: My page
type: landing

sections:
  - block: portfolio
    id: projects
    content:
      title: 我的博客文章
    #   subtitle: My subtitle
      text: |2-
        这里是我的博客。所有的博客文章都在这里。文章涉及的话题非常广，从专业到爱好都有可能涉及，下面有按钮可供筛选话题。

        一般来讲，我并不假定读者具备某些方面的知识。但具体到一篇博文，可能会有前置知识的要求。比如学术相关的文章有可能对非业内读者并不友好。

        学术领域的相关博文很有可能会用英文直接写作，不做翻译，但依然可以在此网站的中文界面（即本页）找到。
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
        - name: 全部文章
          tag: '*'
        - name: 学术研究
          tag: 学术研究
        - name: 学术生涯
          tag: 学术生涯
        - name: 体育话题
          tag: 体育
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
