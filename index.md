---
layout: page
title: Go PHP 7 Extensions
---

# goPHP7 (extensions)

It's time to make extensions first class citizens of the PHP community
 
## The goals of gophp7(ext)

 1. Get PHP extensions running "out of the box" when PHP7 is released (no lag time)
 2. Make extensions in general easier to install and use (binaries, ppas)
 3. Get more people involved in extension maintainance (and travis/appveyor running on them all, killing off bugs)
 4. Get more documentation written for extension writing
 5. Codify some of the "best practices" of extension writing and design (a la PSR)
  
## Who should get involved?

Anyone who can write PHP!  If you're interested in C or C++ (or you want to learn), if you can help to test, triage bugs, sort documentation, set up ci environments ... you can help us.  We're asking everyone to give us 30 minutes a day, and there are tasks of every level waiting to be done.

The idea is that as a community, this is important to us, and together we can use all our skills to achieve our goals.

## How can I help?

We've got various initiatives going on, jump in wherever you feel most comfortable.

### Catalog PHP extensions

We need to begin by collecting information to work out what is needed.  We'll be using our wiki to create a list of all the PHP extensions we can find out about and to record their status, their maintainers, and what work needs doing.  There is more information about this task on the [extensions catalog page](extensions-catalog.html).

### Spread the Word

We need to make sure that people know two things:

 * Extensions will break under PHP7 unless they are updated
 * There are places they can help and get help to make that happen

### Help us with development platforms

We're going to need easy ways to help people get up and running.  To start with we're aiming for vagrant boxes to help with quick development setup (joepferguson is in charge) - besides using rasmus's excellent PHP7 box <https://atlas.hashicorp.com/rasmus/boxes/php7dev> we'll also need windows boxes, and possibly some different virtual backends (parallels, hyper-v, vmware) for the php7dev box beyond virtualbox

### Write the documentation for our helpers

If you already know a bit about extensions, or you find more information somewhere (or overhear people getting help in channel), please take a moment to capture those thoughts and offer them as a pull request to this site.

## What else is going on?

We have rather a large TODO list [here](todo.html).

## Contact us

We're in #gophp7-ext on freenode, come and say hi!
