This is the initial README file for a short-lived project.

= About this Document =

There is nothing to see here. I'm just testing a code-review cicle using
GitHub's "Pull Request" feature.

= Bogus section =

This section only exist to change the numbering of the lines bellow it and thus check if comments made in Github follow the lines they were originally ment to.

= Pull requests =

So, the main idea about using Githubs's pull requests for code review is
that its interface allows for commenting files on a line-by-line basis
and other forms of dicussions about the code pertaining the change
purposed by the pull request.

The big question is: do updates in the branch the pull request is comming from
reflect in the pull request? Will comments made to a given line of code move
follow those updates?

= Original documentation =

To see the original docs about Github and its improved pull request head to
https://github.com/blog/712-pull-requests-2-0 .

Kind of off-topic but interesting nevertheless is Github's article about its
Compare View: https://github.com/blog/612-introducing-github-compare-view .
Also check its article on Branch list: https://github.com/blog/611-branch-lists
.

= Other tools for code review =

Gotta tell you that Rietveld (http://codereview.appspot.com/) is actually
pretty good, better than GitHub's offering. The thing is, Github review process
is well integrated with the rest of the site and feels natural. Using Rietveld
with git requires the use of third-party tools like git-cl
(http://neugierig.org/software/git/?r=git-cl) and may seem too odd for people
not used to that kind of code review.
