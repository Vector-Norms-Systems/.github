# Hi there, Welcome to Vector_Norms aka Venom Systems Dev

> A rising company with the aim of driving smart systems into existing and new code bases.

`simple-website-with-blog` is a simple [Node.js](https://nodejs.org/) web application for static content that includes a blog.
It was created as the basis for [my own website](https://dlaa.me/), but everyone is welcome to use it.
The implementation strives to be simple and free of unnecessary dependencies.

## Goals

- An easy way to create a simple, secure website with a blog
- Support for text-based and photo-based blog formats
- Easy authoring in HTML, Markdown (with code formatting), or JSON
- Ordering of posts by publish date or content date
- Easy customization of site layout and formatting
- High resolution (2x) support for photo blog images
- Support for Windows and Linux hosting with Node.js
- Simple post format that separates content and metadata
- Ability to author hidden posts and schedule a publish date
- Ability to create posts that never show up in the timeline
- Support for archive links and tagging of posts by category
- Quick search of post content, including simple search queries
- Automatic Twitter and Open Graph metadata for social media
- Automatic cross-linking of related posts
- No JavaScript requirement for client browsers

## Structure

- `/app.js` Entry point for the application, configures the server and static content
- `/blog.js` Implementation of the blog, archives, tags, search, and RSS
- `/config.js` Environment variables used to control basic behavior
- `/sites/shared.js(x)` Blog layout code shared by the sample sites
- `/sites/sample-text/render.js(x)` Blog layout code for the sample text blog
- `/sites/sample-text/static/...` Static files and directories for the sample text blog
- `/sites/sample-text/posts/...` Post metadata and content for the sample text blog
- `/sites/sample-photo/...` Sample photo blog
- `/sites/test/...` Test site for running unit tests

## Instructions

1. Install Node.js version 12+
1. Fork and clone repository
1. Create directory under `/sites` or use one of the samples
1. Add static content to `/sites/yoursite/static`
1. Add post JSON and content under `/sites/yoursite/posts`
1. `npm install`
1. `npm run compile`
1. `npm start`
1. Open <http://localhost:3000/> and verify
1. Commit changes to repository
1. Deploy repository to hosting service


## Previous Systems

| Project      | Home Page                                    |
|--------------|----------------------------------------------|
| Express      | <https://expressjs.com/>                     |
| React        | <https://reactjs.org/>                       |
| Helmet       | <https://helmetjs.github.io/>                |
| markdown-it  | <https://github.com/markdown-it/markdown-it> |
| highlight.js | <https://highlightjs.org/>                   |
| Lunr         | <https://lunrjs.com/>                        |
| rss          | <https://github.com/dylang/node-rss>         |

## Contributing

- Open issue, discuss proposal
- Fork and clone repository
- Change code and update tests
- `npm test`
- `npm run lint`
- Review changes
- Send pull request




<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
