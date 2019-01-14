---
title: Website configuration information
---

## Shareable NDE Models Working Group Website

The website is hosted with Github and generated with
[Jekyll](https://jekyllrb.com) and [minimal mistakes](https://mmistakes.github.io/minimal-mistakes/)

### Instructions for making changes to this site

1. Clone the site: "git clone git@github.com:nde-modeling/nde-modeling.github.io.git"
2. Set up Jekyll locally so you can test your changes locally before pushing them out to the github repository. See <https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/> for more information.
3. Make your changes and verify them locally
  * Open source packages to be described/included on the site go into the _posts directory. A header with a title, categories, and tags is required. See an existing entry (raw view) for an example. The filename for a new entry MUST be preceded by the date added in YYYY-MM-DD format.
  * Meeting minutes go into the _meetings directory. Be sure to give a correct title and a category of "Meetings"
  * The content of pages is written in the ["kramdown"](https://kramdown.gettalong.org/syntax.html) variant of markdown.
  * Make sure you use the correct category "Packages" and try to re-use existing tags rather than coming up with new ones when possible.
  * Make sure your changes look correct locally. 
4. Commit your changes locally
5. Either create a fork and submit a pull request or push your changes directly to the central repository git@github.com:nde-modeling/nde-modeling.github.io.git.
6. It may take a few minutes for the changes to propagate to the website. The "GitHub Pages" entry under "Settings" on <https://github.com/nde-modeling/nde-modeling.github.io> contains the status of changes being pushed out. It will turn green once the update is complete.

