+++
date = '2026-05-19'
title = 'How This Website Was Created'
draft = false
+++

For my e-portfolio, I chose to build a static website using Hugo. Hugo is a static site generator where the content is written in Markdown files. This approach fits the assignment well, because every blog post can be maintained as a separate file.

The website is hosted using GitHub Pages. This means no separate paid hosting is required, while the website also remains accessible after graduation. The source code of the website is stored in a GitHub repository. Whenever I make changes, I can push a new commit, after which GitHub Actions automatically republishes the website.

I deliberately chose Hugo instead of a traditional CMS such as WordPress because Hugo is lightweight, fast and easy to manage. For this portfolio, I mainly need to publish written reflections and articles, making a full CMS solution unnecessary.

Adding a new post is straightforward. I create a new Markdown file inside the `content/posts/` directory, add the title and date at the top of the file, and then write my reflection. After pushing the changes to GitHub, the website is automatically updated.
