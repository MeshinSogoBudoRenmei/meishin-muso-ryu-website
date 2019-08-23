![Screenshot of homepage](https://github.com/MeshinSogoBudoRenmei/meishin-muso-ryu-website/blob/readme/screenshot.png)

# MeishinMusoRyu.com
This repository contains the source for [MeishinMusoRyu.com](http://meishinmusoryu.com), official website of Meishin Muso Ryu, a Japanese swordsmanship school. Our head is Shuji Matsushita Sensei.

## Requirements

#### Getting Started
- Install Hugo
- Download Hugo theme: `git submodule add https://github.com/digitalcraftsman/hugo-strata-theme.git themes/hugo-strata-theme`
- Start server with drafts enabled: `hugo server -D`

#### Making new blog post
- Create blog post: `hugo new post/name-of-new-post.md`
- When blog post is ready to be published, update its header to say `draft: false`
- Build static pages: `hugo`
- Deploy to GitHub Pages: `git push origin master`

#### Key Dependencies
- [Hugo](https://gohugo.io): open-source static site generator

## Contributors
- [Gary Pang](https://github.com/CodeWritingCow)
- [Michael Luckenbill](https://github.com/mluckenbill)

## References
- [Hugo: Getting Started](https://gohugo.io/getting-started/)
- [Using a Git Submodule for Your Theme](https://forestry.io/docs/troubleshooting/using-a-git-submodule-for-your-theme/)
