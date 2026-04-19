+++
date = '2026-04-19T13:39:11-04:00'
draft = false
title = 'Update Content'
+++

The general method for adding or updating content in Hugo revolves around its CLI and local development server, typically using Markdown files organized within a content/ directory. [1, 2, 3, 4, 5] 
## 1. Adding New Content
To add a new page or post, use the hugo new command from your project's root directory. This command automatically populates the file with "front matter" (metadata) based on your site's archetypes. [3, 6] 

* Command: `hugo new posts/my-new-post.md`
* Result: A new file is created at content/posts/my-new-post.md.
* Metadata: The new file will include a header (YAML, TOML, or JSON) with fields like title, date, and draft: true. [1, 3, 7, 8, 9] 

## 2. Updating Existing Content [10] 
Updating content is as simple as editing the source files directly with any text editor. [4, 11] 

* Edit Files: Open any Markdown file in the content/ folder to change text or front matter.
* Live Preview: Run the local development server with `hugo server -D`.
* LiveReload: Hugo watches for saved changes and automatically refreshes your browser in real-time.
   * Drafts: The -D (or --buildDrafts) flag is required to see content marked as draft: true. [1, 9, 11, 12, 13, 14] 

## 3. Finalizing and Publishing
Once you are satisfied with your changes:

* Disable Draft Mode: Change draft: true to draft: false in the file's front matter.
* Generate Static Files: Run the bare hugo command to build the final production-ready HTML files into the public/ directory.
* Deploy: Upload the contents of the public/ folder to your web host or push changes to a repository linked with a CI/CD tool like GitHub Actions. [1, 9, 11, 12, 14, 15] 

## 4. Deploy to Github
repository: [https://github.com/rzliu/posts](https://github.com/rzliu/posts)

```
git add .
git commit -m "add/update content"
git push origin HEAD:posts
```

Github will re-build and update to Pages at:
[https://rzliu.github.io/posts/](https://rzliu.github.io/posts/)


Would you like to know how to customize the default template used when you create new posts?

- [1] [https://gohugo.io](https://gohugo.io/getting-started/quick-start/)
- [2] [https://gohugo.io](https://gohugo.io/content-management/)
- [3] [https://www.youtube.com](https://www.youtube.com/watch?v=0GZxidrlaRM)
- [4] [https://www.robertmunn.com](https://www.robertmunn.com/blog/hugo-content-workflow/)
- [5] [https://gethinode.com](https://gethinode.com/guides/optimization/#:~:text=Step%205%20%2D%20Assessing%20the%20Site%20in,is%20not%20capable%20of%20compressing%20these%20assets.)
- [6] [https://gohugo.io](https://gohugo.io/commands/hugo_new_content/)
- [7] [https://reshmeeauckloo.com](https://reshmeeauckloo.com/posts/hugo_create-new-post/)
- [8] [https://deno.com](https://deno.com/blog/hugo-blog-with-deno-deploy#:~:text=Add%20a%20blog%20post%20Again%2C%20we%20can,show%20all%20posts%20where%20draft:%20true%20.)
- [9] [https://srdan.geek.nz](https://srdan.geek.nz/posts/friday-2nd-august-2024/)
- [10] [https://victorious.com](https://victorious.com/blog/updating-your-old-content/#:~:text=Your%20content%20strategy%20should%20balance%20the%20need,a%20month%20%E2%80%94%20and%20stick%20with%20it.)
- [11] [https://nathanpetersen.com](https://nathanpetersen.com/2022/05/25/website-update-hugo/)
- [12] [https://merrimanlab.github.io](https://merrimanlab.github.io/post/2020-10-15-making-posts/)
- [13] [https://gohugo.io](https://gohugo.io/getting-started/usage/)
- [14] [https://pitchumanisivan.in](https://pitchumanisivan.in/posts/hugo-new-post/)
- [15] [https://discourse.gohugo.io](https://discourse.gohugo.io/t/how-to-update-hugo-site-with-all-new-posts-which-already-published/37169)

