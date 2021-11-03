# Getting `Git` Good

Version control (a lá [`git`](https://git-scm.com/)) has been standard practice
in software engineering for decades, and its use has started to become expected
in data science. In order to collaborate effectively, it is imperative to use
version control tools alongside collaborative programming platforms like
[GitHub](https://github.com) and [Bitbucket](https://bitbucket.org).

---

## A few "good enough" practices

* Commit often; commits serve as "anchor points" in the history of a project.
  You can return to any point in the project history for which there is
  a commit.
* Always work on new branches when adding features or developing a new line of
  work. Name the branches based on the work that they aim to contribute.
* After the work on a branch is completed, create a [pull
  request](https://help.github.com/articles/about-pull-requests/) to the
  `master` (or `main`) branch of the repository as appropriate.
* I'd recommend reviewing the ["`git` flow" branching
  model](http://nvie.com/posts/a-successful-git-branching-model/). There are
  other models as well.

n.b., These are _opinionated_ takes of mine, and many may disagree with them. As
you learn more about version control best practices, you may find alternative
frameworks/guidance that better suite your, and your team's, work style.

---

## Resources

Here are a few useful notes and readings that may be useful in remedying any
problems that may arise when working with `git`. These range the spectrum from
applied to fairly technical:

* ["Version Control with `git`" (Software
    Carpentry)](https://swcarpentry.github.io/git-novice/) - a comprehensive
    introduction to the uses of `git` and social coding with GitHub. This is
    aimed towards students and research professionals.
* ["Happy `git` and GitHub for the useR" (Jenny Bryan,
    RStudio)](http://happygitwithr.com/) - a comprehensive introduction to both
    the inner workings of `git` and best practices in using GitHub, with a focus
    on integrating these tools into your R workflow -- aimed towards
    masters-level university students.
* ["Tools for Reproducible Research" (Karl
    Broman)](http://kbroman.org/Tools4RR/) - a University-level course on best
    practices in modern reproducible research, which includes a couple of
    lectures on `git` and GitHub.
    * ["Version Control with `git` and
        GitHub"](http://kbroman.org/Tools4RR/assets/lectures/04_git.pdf)
* ["Introduction to `git`" (Berkeley's Stat 159/259, Fall 2015, KJ
    Millman)](http://www.jarrodmillman.com/rcsds/standard/git-intro.html) - a
    thorough walkthrough of some common `git` commands as well as explanations
    of what these commands do when invoked.
