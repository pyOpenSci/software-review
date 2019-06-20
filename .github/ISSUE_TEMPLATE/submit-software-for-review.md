---
name: Submit Software for Review
about: Use to submit your Python package for peer review
title: ''
labels: 1/editor-checks, New Submission!
assignees: ''

---

Submitting Author: Name (@github_handle)  
Package Name: 
One-Line Description of Package: 
Repository Link:  
Version submitted:   
Editor: TBD  
Reviewer 1: TBD  
Reviewer 2: TBD  
Archive: TBD  
Version accepted: TBD   

---

## Description

- Include a brief paragraph describing what your package does:

## Scope 
- Please indicate which [category or categories](https://www.pyopensci.org/dev_guide/peer_review/aims_scope.html) this package falls under:
	- [ ] Data retrieval
	- [ ] Data extraction
	- [ ] Data munging
	- [ ] Data deposition
	- [ ] Reproducibility
	- [ ] Geospatial
	- [ ] Education
	- [ ] Data visualization*

\* Please fill out a pre-submission inquiry before submitting a data visualization package. For more info, see [this section](https://www.pyopensci.org/dev_guide/peer_review/aims_scope.html#notes-on-categories) of our guidebook.

- Explain how the and why the package falls under these categories (briefly, 1-2 sentences):

-   Who is the target audience and what are scientific applications of this package?  

-   Are there other Python packages that accomplish the same thing? If so, how does yours differ?

-   If you made a pre-submission enquiry, please paste the link to the corresponding issue, forum post, or other discussion, or `@tag` the editor you contacted:

## Technical checks

For details about the pyOpenSci packaging requirements, see our [packaging guide](https://www.pyopensci.org/dev_guide/packaging/packaging_guide.html). Confirm each of the following by checking the box.  This package:

- [ ] does not violate the Terms of Service of any service it interacts with. 
- [ ] has an [OSI approved license](https://opensource.org/licenses)
- [ ] includes documentation with examples for all functions.
- [ ] contains a vignette with examples of its essential functions and uses.
- [ ] has a test suite.
- [ ] has continuous integration, such as Travis CI, AppVeyor, CircleCI, and/or others.

## Readme Requirements
### README
All packages should have a user-friendly README.md in their root directory. The README should include, from top to bottom:

- [ ] The package name
- [ ] Badges for continuous integration and test coverage, the badge for pyOpenSci peer-review once it has started (see below), a repostatus.org badge, and any other badges. If the README has many more badges, you might want to consider using a table for badges, see this example, that one and that one. Such a table shoud be more wide than high.
- [ ] Short user-friendly description of goals of package. Please try to make this language accessible to anyone who might be interested in using this package including new users. 
- [ ] Descriptive links to all vignettes (rendered, i.e. readable, cf the documentation website section) unless the package is small and there’s only one vignette repeating the README.
- [ ] Installation instructions
- [ ] Any additional setup required (authentication tokens, etc)
- [ ] Brief demonstration of package use
- [ ] Direction to more detailed documentation (e.g. links to documentation files or a website).
- [ ] If applicable, how the package compares to other similar packages and/or how it relates to other packages
- [ ] Citation information
- [ ] Contribution guidelines (as a link or in the readme as you prefer)
- [ ] Instructions for installing the development version of the package

## Usability Requirements

## Publication options

- [ ] Do you wish to automatically submit to the [Journal of Open Source Software](http://joss.theoj.org/)? If so:

<details>
 <summary>JOSS Checks</summary>  

- [ ] The package has an **obvious research application** according to JOSS's definition in their [submission requirements](https://joss.readthedocs.io/en/latest/submitting.html#submission-requirements). Be aware that completing the pyOpenSci review process **does not** guarantee acceptance to JOSS. Be sure to read their submission requirements (linked above) if you are interested in submitting to JOSS. 
- [ ] The package is not a "minor utility" as defined by JOSS's [submission requirements](https://joss.readthedocs.io/en/latest/submitting.html#submission-requirements): "Minor ‘utility’ packages, including ‘thin’ API clients, are not acceptable." pyOpenSci welcomes these packages under "Data Retrieval", but JOSS has slightly different criteria.
- [ ] The package contains a `paper.md` matching [JOSS's requirements](https://joss.readthedocs.io/en/latest/submitting.html#what-should-my-paper-contain) with a high-level description in the package root or in `inst/`.
- [ ] The package is deposited in a long-term repository with the DOI: 

*Note: Do not submit your package separately to JOSS*
  
</details>

## Are you OK with Reviewers Submitting Issues to your Repo Directly?
This option will allow reviewers to open smaller issues that can then be linked to PR's rather than submitting a more dense text based review. It will also allow you to demonstrate addressing the issue via PR links.

- [ ] Yes I am OK with reviewers submitting requested changes as issues to my repo. Reviewers will then link to the issues in their submitted review.

## Code of conduct

- [ ] I agree to abide by [pyOpenSci's Code of Conduct](https://www.pyopensci.org/dev_guide/peer_review/coc.html) during the review process and in maintaining my package should it be accepted.


**P.S.** *Have feedback/comments about our review process? Leave a comment [here](https://github.com/pyOpenSci/governance/issues/8)*

## Editor and Review Templates

[Editor and review templates can be found here](https://www.pyopensci.org/dev_guide/appendices/templates.html)
