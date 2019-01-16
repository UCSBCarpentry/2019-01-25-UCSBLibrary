# UCSB Software Carpentry Workshop 1/25-26/2019

This repository was created from The Carpentries' ([Software Carpentry][swc-site], [Data Carpentry][dc-site], and [Library Carpentry][lc-site]'s)
template for creating websites for workshops.

###Prep List###
  - 1/22 team session
    - pair up to practice our sections
  - 1/23 team session
    - in rm 1312 to practice with a/v equipment


## Don't forget to do this:
~~3.  Once you are done, please also [let us know][email] the workshop URL.~~ 
If this is a self-organised workshop, you should also [fill in the self-organized workshop form][self-organized-workshop-form] (if you have not already done so), so we can keep track of all workshops. We build the list of workshops on our websites from the data included in your `index.md` page. We can only do that if you [customize][customization] that page correctly *and* let us know the workshop URL.

## Setting Up a Separate Repository for Learners

If you are teaching Git,
you should create a separate repository for learners to use in that lesson.
You should not have them use the workshop website repository because:

*   your workshop website repository contains many files
    that most learners don't need to see during the lesson,
    and

*   you probably don't want to accidentally merge
    a damaging pull request from a novice Git user
    into your workshop's website while you are using it to teach.

You can call this repository whatever you like,
and add whatever content you need to it.


**Note:**
This workshop consists of 3 canonical Carpentry lessons:  Bash, git, and R.  All episodes, figures, and data from those lessons are in the appropriate directories of this repo.

**Note:**
please do all of your work in your repository's `gh-pages` branch,
since [GitHub automatically publishes that as a website][github-project-pages].

**Note:**
See the [design notes][design] for more information about editing workshops and lessons.

Further instructions are available in [the customization instructions][customization].
This [FAQ][faq] includes a few extra tips (additions are always welcome)
and these notes on [the background and design][design] of this template may help as well.

## Creating Extra Pages

If you want to add extra pages to your workshop website.
You can do this by putting either Markdown or HTML pages in the website's root directory
and styling them according to the instructions give in
[the lesson template][lesson-example].
If you do this,
you *must* also edit `_config.yml` to set these three values:

1.  `carpentry` is either "dc" (for Data Carpentry), "swc" (for Software Carpentry),
    or "lc" (for Library Carpentry). This determines which logos are loaded.

2.  `title` is the title of your workshop (typically the venue and date).

3.  `email` is the contact email address for your workshop,
    e.g., `gvwilson@miskatonic.edu`.

Note: `carpentry` and `email` duplicate information that's in `index.md`,
but there is no way to avoid this
without requiring people to edit both files in the usual case
where no extra pages are created.



## Getting and Giving Help

We are committed to offering a pleasant setup experience for our learners and organizers.
If you find bugs in our instructions,
or would like to suggest improvements,
please [file an issue][issues]
or [mail us][email].

[email]: mailto:team@carpentries.org
[customization]: https://carpentries.github.io/workshop-template/customization/
[dc-site]: http://datacarpentry.org
[design]: https://carpentries.github.io/workshop-template/design/
[faq]: https://carpentries.github.io/workshop-template/faq/
[github-project-pages]: https://help.github.com/articles/creating-project-pages-manually/
[importer]: https://github.com/new/import
[issues]: https://github.com/carpentries/workshop-template/issues
[jekyll-windows]: http://jekyll-windows.juthilo.com/
[jekyll]: https://jekyllrb.com/
[lesson-example]: https://carpentries.github.io/lesson-example/
[pyyaml]: https://pypi.python.org/pypi/PyYAML
[ruby-install-guide]: https://www.ruby-lang.org/en/downloads/
[ruby-installer]: http://rubyinstaller.org/
[rubygems]: https://rubygems.org/pages/download/
[self-organized-workshop-form]: https://amy.software-carpentry.org/workshops/submit/
[swc-site]: http://software-carpentry.org
[lc-site]: https://librarycarpentry.org
