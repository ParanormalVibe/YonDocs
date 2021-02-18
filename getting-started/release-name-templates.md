---
title: release-name-templates
description: 
published: true
date: 2021-02-18T02:17:54.326Z
tags: 
editor: undefined
dateCreated: 2021-02-17T23:32:24.348Z
---

# Release Name Templates

## Summary
We use release name templates to create a version tree by extracting information from file names. Previously, file names would adhere to a user-defined template that we would splice and insert into a tree accordingly. In anticipation of the broadening of Yon's scope, we made it so that release name templates aren't used to process file names directly but instead used to process release names.

## Syntax
Consider the following example in which the release name template is for a video game that uses semantic versioning. A release name template for such a game might look like this: `Video Game v{Major Version}.{Minor Version}.zip`. 

Release name templates consist of characters enclosed within curly brackets to indicate parts of the release name that can differ between releases, and characters outside of curly brackets indicate parts of the release name that will always stay the same. Release name templates must have at least one set of curly braces to be considered valid.`

## See Also
- [Implementation]()
- [GitHub Issues](https://github.com/ParanormalVibe/Yon/labels/Release%20Name%20Template)