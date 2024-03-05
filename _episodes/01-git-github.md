---
title: "Version Control with Github Desktop"
teaching: 30
exercises: 10
questions:
- "How do you record the history of your projects?"
- "What is version control?"
objectives:
- "Present overview of version control."
- " "
keypoints:
- "Version control is an integral part of reproducible research"
- "Manipulate data in a reproducible manner"
output:  
      html_document
---



> ## Prerequisites
>
> - Create GitHub account
> - [Install page](https://desktop.github.com/?ref_cta=download+desktop&ref_loc=installing+github+desktop&ref_page=docs)
{: .prereq}

## Recording the history of your projects

### What is version control?

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

## Question?

How do you record the history of your projects?

### Bad - Run on file names

![](../fig/phd101212s.png)

[PhD Comics](http://www.phdcomics.com)

### Good - Informatively named files

```
   2013-10-14_manuscriptFish.doc
   2013-10-30_manuscriptFish.doc
   2013-11-05_manusctiptFish_intitialRyanEdits.doc
   2013-11-10_manuscriptFish.doc
   2013-11-11_manuscriptFish.doc
   2013-11-15_manuscriptFish.doc
   2013-11-30_manuscriptFish.doc
   2013-12-01_manuscriptFish.doc
   2013-12-02_manuscriptFish_PNASsubmitted.doc
   2014-01-03_manuscriptFish_PLOSsubmitted.doc
   2014-02-15_manuscriptFish_PLOSrevision.doc
   2014-03-14_manuscriptFish_PLOSpublished.doc
```

## Better - Saving everything together at once

Everytime you make a save, you zip the entire directory that your project files are in and save it with a date.

## Best - Version Control

![](../fig/motivation-01.png)

[Code for `RNeXML` `R` package, plus RNeXML publication in `RMarkdown`](https://github.com/ropensci/RNeXML)

## How does a version control system work?

- Version control systems start with a base version of the document and then save just the changes you made at each step of the way.
- You can think of it as a tape: if you rewind the tape and start at the base document, then you can play back each change and end up with your latest version.

![](../fig/play-changes.png)

[Software Carpentry](https://software-carpentry.org/)

- You can then think about "playing back" different sets of changes onto the base document and getting different versions of the document.

![](../fig/merge.png)

[Software Carpentry](https://software-carpentry.org/)

## Why use Git and GitHub

### Why use Git?

- Makes you fearless
- Easy to set up
- Allows you to take a snapshot of every stage of your project history
- Takes up minimal space
- Creates a easy navigable map to the history of all changes made

### Features of using a Hosting Service Like GitHub

- Backup of your project
- No need for a server: easy to set up
- GitHub's strong community: your colleagues are probably already there
- Provides tools to help enhance collaboration
- A common location to share off your work

### Example

![](../fig/motivation-01.png)

[Code for `RNeXML` `R` package, plus RNeXML publication in `RMarkdown`](https://github.com/ropensci/RNeXML)
