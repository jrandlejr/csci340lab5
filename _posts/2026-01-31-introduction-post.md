---
layout: post
title: "Introduction Post"

---

Setting up my first Jekyll blog went pretty smoothly overall!

The first few steps (1 through 6) were straightforward.I installed Ruby, set up Jekyll, created the repo, and got the local server running with `jekyll serve`. Seeing the site appear at http://127.0.0.1:4000 right away was exciting and made everything feel real.

Here are some things that were **new** to me:
- What **YAML front matter** actually does (those `---` blocks at the top for metadata like title and layout)
- Why every post file **must** start with a date in `YYYY-MM-DD-` format (so Jekyll knows when to publish and sorts them correctly)
- How **Liquid** tags work inside Markdown, like the code highlighting blocks
- The automatic build process when pushing to GitHub Pages

Parts I struggled with:
- Forking Dr. Goadrich's repository was the trickiest part. I ran into the usual tech hiccups after clicking Fork, the new repo didn't show up immediately in my list of repositories. It felt like nothing happened at first, which was frustrating. I refreshed a few times, double-checked I was logged in correctly, and eventually it appeared. Once it did, I could clone it locally and move forward. Classic GitHub delay glitch, but I got it handled!

Things that still don't fully make sense yet:
- The deeper details of how Liquid variables (like `site.posts`, `page.title`, or `site.url`) get populated from the config and files
- When to use layouts vs. includes vs. collections (I get that layouts are the main page templates, but the others are still a bit confusing)

I'm really looking forward to:
- Customizing the look of the blog (maybe add some CSS or a theme)
- Posting updates about what I'm learning in Databases and Web Systems this semester
- Experimenting with more features like images, embedded code, or even basic interactivity later on

Two helpful links I checked out during setup:
- The [official Jekyll docs on writing posts](https://jekyllrb.com/docs/posts/) — great for nailing the filename and front matter rules
- GitHub's guide on [forking a repository](https://docs.github.com/en/get-started/start-your-journey/fork-a-repo) — super clear steps (even if there was a little wait after clicking Fork)

Overall, I'm glad I powered through the fork issue!Now, the blog is up and running. Excited for more labs!