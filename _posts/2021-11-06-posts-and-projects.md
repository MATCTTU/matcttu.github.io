---
layout: post
title:  "3. Adding posts and projects"
date: 2021-11-06
excerpt: "Learn how to add portfolio pieces and blog posts."
project: true
tags:
- GitHub
comments: true
---

## Adding posts

Posts and projects both live in the `_posts` folder. The only difference is that projects have the line `project: true` in the front matter. The front matter is everything between the ---s at the beginning of the file.

For new posts, use the following template:

```
---
layout: post
title:  "Put your title here"
date:   2021-04-31
excerpt: "This is a short description that should entice readers to want to read the full text."
tag:
- keyword
- other keyword
- etc...
feature: https://i.imgur.com/fU0XhVE.jpg
comments: true
---
```

1. From the main repo page click **_posts**

1. Click **Add a file**, and then click **Create a file**.

1. Enter the name of your blog post in the following format `year-month-day-project-title.md`, for example `2021-04-31-my-first-post.md`

   > Note that everything following the day will make up the post's URL, so keep it short.

1. Copy and paste the template from above into the file.

1. Customize the front matter. Additionally, you may
    - Replace the link in `feature: https://i.imgur.com/fU0XhVE.jpg` with a link or path to the image you want to use.
    - Delete the `feature: https://i.imgur.com/fU0XhVE.jpg` line to create a project or post without an image.
    - Add or delete tags to be able to categorize your posts and projects on the [tags page](https://matcttu.github.io/tags/)

1. Underneath the 3 closing hyphens, write `Hello, world!`, and then click **Commit changes**. Note that it may take up to 10 minutes for your changes to rollout.

   You have just created your first post. For help with additional Markdown formatting and styling, see the [Markdown syntax page source](https://github.com/MATCTTU/matcttu.github.io/blob/master/_posts/2016-03-20-markdown-syntax.md) and [rendered page](https://matcttu.github.io/markdown-syntax/).

## Adding projects

For new projects, start with the following template:

```
---
layout: post
title:  "Put your title here"
date:   2021-04-31
excerpt: "This is a short description that should entice readers to want to read the full text."
project: true
tag:
- keyword
- other keyword
- etc...
feature: https://i.imgur.com/fU0XhVE.jpg
comments: true
---
```

Note that the only difference is adding the line `project: true` to the front matter.

1. From the main repo page click **_posts**

1. Click **Add a file**, and then click **Create a file**.

1. Enter the name of your project in the following format `year-month-day-project-title.md`, for example `2021-04-31-my-first-project.md`

   > Note that everything following the day will make up the post's URL, so keep it short.

1. Copy and paste the template from above into the file.

1. Customize the front matter. Additionally, you may
    - Replace the link in `feature: https://i.imgur.com/fU0XhVE.jpg` with a link or path to the image you want to use.
    - Delete the `feature: https://i.imgur.com/fU0XhVE.jpg` line to create a project or post without an image.
    - Add or delete tags to be able to categorize your posts and projects on the [tags page](https://matcttu.github.io/tags/)

1. If you have an existing portfolio piece, you can copy/paste the content after the 3 closing hyphens. If you don't have a portfolio piece handy, you can generate, copy, and paste placeholder text from [Hipster Ipsum](https://hipsum.co/).

1. Once you've added text, scroll all the way down and click **Commit changes**. Note that it may take up to 10 minutes for your changes to rollout.

   You have just created your first project. For help with additional Markdown formatting and styling, see the [Markdown syntax page source](https://github.com/MATCTTU/matcttu.github.io/blob/master/_posts/2016-03-20-markdown-syntax.md) and [rendered page](https://matcttu.github.io/markdown-syntax/).

### Deleting posts and projects

1. From the main repo page click **_posts**

1. Click `2021-11-08-getting-started.md`.

1. In the upper-right corner, lick the Trashcan icon.

1. Scroll all the way down, and then click **Commit changes**. Note that it may take up to 10 minutes for your changes to rollout.

   Repeat these steps to delete the other template content.
