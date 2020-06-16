# static-marks-github-pages

[static-marks](https://github.com/darekkay/static-marks) converts plain yaml bookmark files into a static web app.
This template is deploying it to  Github-Pages using the [github-pages-action](https://github.com/marketplace/actions/github-pages-action) on a commit on master.

Share and search bookmarks without 3rd-party-software, allow everybody in your team editing it.

Use a bookmark-keyword to immediately search your bookmarks, i.e. firefox:

* bookmark a link like with an %s-placeholder, i.e. `https://{user}.github.io/{repo}/?search=%s`
* give it keyword, i.e. `b`
* type in your browsers address-bar `b chocolate`

See the example here: [https://gaerfield.github.io/static-marks-github-pages](https://gaerfield.github.io/static-marks-github-pages)

# Usage

1) click on the friendly green button "Use this template"
2) choose a name and make the repository public (otherwise github-pages wouldn't be possible)
2) Repository-Settings -> Options -> github-pages -> source -> gh-pages Branch (enforce https)
3) edit the bookmark.yml-File within the root-directory (just do it in github, no need to clone it) 
4) commit
5) check youre url github-page on `https://{user}.github.io/{repo}`

