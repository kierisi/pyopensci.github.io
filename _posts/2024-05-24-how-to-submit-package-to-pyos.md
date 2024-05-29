---
layout: single
title: "How to: submitting a package to pyOpenSci"
excerpt: "This step-by-step guide will walk you through submitting a package to pyOpenSci's open peer review process."
author: "Jesse Mostipak"
permalink: /blog/how-to-submit-a-package-to-pyopensci.html
header:
  overlay_image: images/blog/2024/may/submitting-a-package.png
  overlay_filter: 0.6
categories:
  - blog-post
  - community
classes: wide
toc: true
comments: true
---
# <i class="fa-solid fa-screwdriver-wrench"></i> Congratulations, you’ve created a package!
Creating a Python package, whether it's your first or five-hundredth, is an incredible contribution to the open source ecosystem---don't forget to take a moment to celebrate! But the adventure doesn't have to stop there. You can also submit your package to pyOpenSci's open peer review process.

> Looking for help creating a Python package? Check out [the pyOpenSci Package Guide](https://www.pyopensci.org/python-package-guide/), which will walk you through the process, start to finish.

# <i class="fa-solid fa-circle-chevron-down"></i> Why you should submit to pyOpenSci's open peer review process
pyOpenSci's peer review process is run by a team of dedicated volunteers, and provides the opportunity for package maintainers to have their code, documentation, and infrastructure vetted by both domain experts as well as Python experts. Because pyOpenSci invests in recruiting a diverse team of editors and reviewers, our review process provides and enhanced feedback experience.

In addition, pyOpenSci's partnership with the [Journal of Open Source Software](https://www.pyopensci.org/software-peer-review/partners/joss.html) means that if your package is accepted by pyOpenSci and in scope for JOSS, it will be fast-tracked through JOSS’ review process.

Read more about the benefits of utilizing pyOpenSci's open peer review process in our [Peer Review Guide](https://www.pyopensci.org/software-peer-review/about/benefits.html).

# <i class="fa-solid fa-magnifying-glass"></i> What pyOS looks for in a package
When submitting to pyOpenSci, there are several criteria we use to evaluate if the package is in-scope for our review process:
1. Package maintenance: we understand that life happens, but we ask that you commit to maintaining your package for at least 1-2 years after the pyOpenSci review process is complete.
2. Your package should meet all of the initial Editor checks, which include:
- **Installation:** the package can be installed from a community repository such as PyPI (preferred), and/or a community channel on conda (e.g. conda-forge, bioconda).
- **Fit:** the package meets criteria for [fit](https://www.pyopensci.org/software-peer-review/about/package-scope.html#what-types-of-packages-does-pyopensci-review) and [overlap](https://www.pyopensci.org/software-peer-review/about/package-scope.html#package-overlap).
- **Documentation:** the package has sufficient online documentation to allow us to evaluate package function and scope *without installing the package*.
- **GitHub:** core GitHub repository files are present.
- **Issue submission documentation:** all of the information is filled out in the `YAML` header of the issue (located at the top of the issue template).
- **Automated tests:** the package has a testing suite and is tested via a Continuous Integration service.
- **Repository:** the repository link resolves correctly.
- **Package overlap:** The package doesn't entirely overlap with the functionality of other packages that have already been submitted to pyOpenSci.
- **Archive** (JOSS only, may be post-review): The repository DOI resolves correctly.
- **Version** (JOSS only, may be post-review): Does the release version given match the GitHub release (v1.0.0)?
- **Survey:** the initial onboarding survey was filled out.

You can get more details about each of these criteria in our [Authors Guide](https://www.pyopensci.org/software-peer-review/how-to/author-guide.html).

# <i class="fa-brands fa-github-alt"></i> Choosing the correct issue for submission via GitHub
<figure>
    <a href="/images/blog/2024/may/issue-selection-screen.png">
    <img src="/images/blog/2024/may/issue-selection-screen.png" style="max-width:100%" alt="Screenshot of the pyOpenSci issue selection screen on GitHub, with three options: Help Request, Presubmission Inquiry, and Submit Software for Review.">
    </a>
    <figcaption>
      There are three options when you reach the pyOpenSci issue selection screen.
    </figcaption>
</figure>


* Screenshot of software-submission page, create a decision tree graphic
* Help request explanation
* Pre-submission inquiry explanation
* A note on data visualization packages—all data viz packages should go through pre-submission inquiry (to evaluate scope?)
* Submit Software for review explanation

# <i class="fa-solid fa-heart"></i> Submit for review: using an issue template
We’re going to use Submit Software for review
Overview of the GitHub UI
Labels
Write//preview
Markdown basics
Call-out: link to Markdown 101 resource (could make a nice quick blog post, too)
What is an issue template?
Standardizes the submission process
Etiquette:
Keep things as they are–don’t delete, rearrange, reformat….

# <i class="fa-solid fa-map"></i> Step-by-step: filling out the submission for review issue template
Fill out an exemplar issue that someone can follow along with. Use two images side-by-side: blank (before) and filled-in (after), going section by section
Logistics:
Submit all at once
Recommend reading through a few times, but at a high level, in addition to having your package, you’ll want to know:
Scope of your package (see categories)
Target audience
Scientific applications of the package
Other packages that accomplish the same thing (if any), and how yours is different
Let’s start at the very beginning: writing a title
Keeping it simple
Package name: short description
Header
You fill out author, maintainers, name, one-liner, repo link, version submitted
You don’t need to worry about: editor, reviewer 1, reviewer 2, archive, JOSS DOI, version accepted, or date accepted
Code of Conduct and Commitment to Maintain
Link to CoC, etc. in tutorial
Provide highlights
Description
Scope
Is there more information I can provide here about what we do and do not accept?
Domain specific
Community Partnerships
How to know if your package is associated with an existing community
Technical checks
Links to OSI approved license information
Explain what each component is and why it's important for submission
Submitting to JOSS
Links from issue in tutorial
Submitting directly to your repo
Why we ask this
Confirmation
Link to author guide
Survey
How it helps pyOS
How long it takes to fill out
Feedback
Let us know what you like, dislike, and would like to see changed
Editor and Review templates
Not something you need to worry about!

# <i class="fa-solid fa-hourglass"></i> What’s next: the waiting game
Relax, be ready (to make adjustments)
Once submit, EIC reviews package for scope and infrastructure
Takes about two weeks
May take longer if changes need to be implemented
Entire process can take approximately 3 months, but can also take considerably longer–entirely package-dependent
Full timeline

# <i class="fa-regular fa-comments"></i> Talk to us!
If you found this how-to guide useful, or if you have suggestions for how to improve it, we'd love to hear from you! You can always reach out to us on [Fosstodon](https://fosstodon.org/@pyOpenSci), [LinkedIn](https://www.linkedin.com/company/pyopensci), or our [Discourse forum](https://pyopensci.discourse.group/)!
