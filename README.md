# Badges

| Aspect | Badge |
|:-|:-:|
| Code quality checklist | [![cii best practices](https://bestpractices.coreinfrastructure.org/projects/1811/badge)](https://bestpractices.coreinfrastructure.org/projects/1811)  |
| Continuous integration | [![Build Status](https://travis-ci.org/research-software-directory/research-software-directory.svg?branch=master)](https://travis-ci.org/research-software-directory/research-software-directory) [![Build status](https://ci.appveyor.com/api/projects/status/vki0xma8y7glpt09/branch/master?svg=true)](https://ci.appveyor.com/project/NLeSC/xenon-cli/branch/master)  |
| persistent identifier, citation | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1154130.svg)](https://doi.org/10.5281/zenodo.1154130) |
| Community registry | [![Research Software Directory](https://img.shields.io/badge/rsd-xenon-00a3e3.svg)](https://www.research-software.nl/software/xenon) |

_(Customize these badges with your own links.)_

# Welcome

The repository [https://github.com/NLeSC/template](https://github.com/NLeSC/template) contains the template for software projects at the Netherlands
eScience Center. In principle, it follows the general recommendations from
https://fair-software.nl for developing research software, while adding details that are specific to the Netherlands eScience Center. 

When starting a new project, first fork this repository to your own GitHub organization (if you have one), and mark it as 'template repository' in the newly forked repository's settings (``https://github.com/<your-github-org>/template/settings``).

Next, make a new repository. GitHub should prompt you to use the template as a starting point.

## Use a publicly accessible repository with version control

We use ``git`` in combination with GitHub. Get started with learning ``git`` using these [Software Carpentry lessons](https://swcarpentry.github.io/git-novice/).

## Add a software license

We use the Apache-2.0 license.

## Register your code in a community registry

The Netherlands eScience Center has its own software portfolio at [research-software.nl](https://research-software.nl). If your software has some significant time or money from the Netherlands eScience Center in it, AND we can realistically claim (co)-ownership of the software, submit your software to the Research Software Directory using its admin interface. [This document](https://github.com/research-software-directory/research-software-directory/blob/master/docs/instruction/README.md) explains how to do that.

## Enable citation

[This document](https://guide.esciencecenter.nl/citable_software/making_software_citable.html) describes how to make your software citable using the Citation File Format in combination with the GitHub-Zenodo integration.

## Use a code quality checklist

We use the [Core Infrastructures Initiative checklist](https://bestpractices.coreinfrastructure.org/en). You'll find that it covers many aspects of developing code, some of which may not apply to your project. It's perfectly fine to not be compliant with those, as long as you're transparent on why that is.


# Documentation for users

- _description of what the software does_
- _notes on how to install_

# Documentation for developers

- _notes on how to contribute_

# Documentation for maintainers

- _notes on how to make a release_

