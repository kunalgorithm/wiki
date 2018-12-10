# Meta

- The contents of this wiki is written entirely in Markdown. I chose markdown because it is the standard format for documentation in software development and on Github. Also, it allows for the creation of formatted content without relying on any one application or word-processing software.

  - I considered using [MDX][1] to support JSX/React Components, but ultimately decided against it.

- This entire wiki is contained in one folder and hosted on my [Github][2]. It contains markdown files and layers of subfolders.

- This wiki is published with [Gitbooks][3] Legacy, which integrates with my Github account to automatically publish all changes pushed to the repository. My custom domain name (currently and temporarily [`wiki.kunal.space`][4] ) points and directly visitors to the published website.

- I use `git` from the command line to save and push changes to be published to Github.

  ![git-push][assets/git-push.png]

## Writing and Making Changes

- I create folders and make other structural changes to the wiki using the command line or Sublime Text.
- I write content using [Typora][5] because it's the simplest, most good-looking, distraction-free markdown editor I've found. I've previously used VSCode or Sublime text to write raw markdown directly.
- ![Typora][assets/typora.png]
- My wiki is locally stored under my Dropbox Account, so I can made edits on my phone using the [Ulysses][6] app.

## Content Structure

Each topic will have a title, some description of it, usually my own thoughts and knowledge on it as well as referencing some resources or links I have liked or used that helped me either understand the topic or gain appreciation of it.

Each post will typically be structured as such:

```markdown
# Title

Description of my general thoughts on the topic, just to personalize and contextualize the topic a bit.

## Subtopics

Various subtopics in order of relevance or importance

## Notes

A discussion of what I found interesting, provocative, thoughtful, etc.

## Links

Links related to learning (more) about the topic.
```

[1]: https://github.com/mdx-js/mdx
[2]: https://github.com/kunalgorithm/wiki
[3]: legacy.gitbook.com
[4]: wiki.kunal.space
[5]: typora.io
[6]: ulysses.app
