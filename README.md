About
====================

This helps solve a problem for me, as my company requires that I use a company-specific github account, but when I want to work on other open-source projects, I can't use the company-specific account. I've solved this by storing profiles in the global `.gitconfig` and writing a simple script to override a project's config with a profile, if necessary.

TLDR: quick switching between github accounts


Installation
====================

Clone this repo and add `bin/github-profile` to your PATH


Usage
====================

To add a profile to be used globally:

`github-profile add --profile mculp --email culpepper.matthew@gmail.com --name "Matt Culpepper"`


To switch to a profile within a specific project:

`github-profile use --profile mculp`


Future
====================

* tie into ~/.ssh/config to switch hosts on a per-project basis
