title: "Cindy Hernandez"
author: "Cindy Hernandez"
description: "Emory University"
permalink: /:title/
lang: "en"
excerpt_separator: "\n\n\n"
date_format: "%B %d, %Y"
# Layout
show_social: true         # show footer
show_excerpts: false       # show article excerpts on the home page
show_frame: false           # adds a gray frame to the site
show_sidebar: false        # show a sidebar instead of the usual header
# Menu

navigation:                # accepts {file, title, url, icon, sidebaricon}
  - {file: "index.md"}
  - {file: "/cindy.pdf", title: CV}
  - {url: "/cindy.pdf", title: CV}
  - {file: "blog.md"}

external:                  # shows a footer with social links - for available icons see fontawesome.com/icons
  - {title: Mail, icon: envelope, url: "mailto:cindyguerra.h@outlook.com"}
  - {title: Github, icon: github, url: "https://github.com/saidcindy"}
remote_theme: niklasbuschmann/contrast@v2.11
plugins:
  - jekyll-remote-theme
  - jekyll-feed
