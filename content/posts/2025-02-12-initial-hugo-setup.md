---
title: Initial Hugo setup
description: ""
date: 2025-02-12T13:10:56.444Z
preview: ""
draft: false
tags: []
categories: []
---
Source: https://gohugo.io/getting-started/quick-start/  
Source: https://gohugo.io/installation/windows/

1. Powershell  
   * `winget install Hugo.Hugo.Extended`
   * `winget install --id Git.Git -e --source winget`
2. Restart Powershell  
3. Navigate to wherever the files will be located
4. hugo new site [name of site]
5. cd [name of site]
6. git init
7. Install theme `git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke`
8. Set theme `echo "theme = 'ananke'" >> hugo.toml`
9. Important step for setting up front matter  'hugo new content content/posts/my-first-post.md'
10. To start `hugo server`

Set name of site by editing hugo.toml file