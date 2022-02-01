---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Algorithms for lattice problems in NP cap CoNP
---

This site is dedicated to organizing and presenting what is known about the class of lattice problems that may have efficient algorithms.  It is intended to be a living document that is updated as information comes in and as time permits.  

The goal is to advance research on lattice algorithms.  There are some impediments to working in this area such as its breadth, its increasingly technical nature, notational and language differences, the amount of folklore, and so on.  This site provides an opportunity to have everything relevant to lattice algorithms written in one place, from one point of view, with consistent terminology, and targeted for a broader audience.  Making it available to a broader audience can help build confidence that certain ranges may be difficult to solve.


Here is a picture from [arxiv.org/2201.13450](https://arxiv.org/abs/2201.13450):

<center>
<img  
  src = "assets/img/pic-ranges.pdf"
  width="75%">
</center>
 
The right three regions represent NP intersect CoNP, but most work has focused on the left two regions.  From an algorithms perspective, the natural approach is to push from the right side where algorithms are known.  Let's do that and determine where the boundaries are.


To participate send email to {{ site.email }}.  Suggestions about all topics related to this site are welcome.  This includes technical information, how to organize topics, how to visualize what is known, anything at all.  Help can be public, private, or anoymous.  

## Questions

1. Which subexponential approximation factor assumptions have been made for fully-homomorphic encryption, and how do they relate to the recent algorithms?

## Ideas

1. Lots!  But how to organize them and work through them?

## Open Problems

1. The driving question, way off in the distance: does a polynomial-time algorithm exist for solving any lattice problems with polynomial approximation factor?

## Ideas that don't work

Hmmmm.

# Road blocks 

Besides not finding an algorithm yet, are there other ways to describe why the various problems might or might not have an efficient algorithm? 

# This site

This site was inspired by the recent confusion caused by the responses to the recent paper about a [quantum algorithm for lattice problems](https://arxiv.org/abs/2201.13450).

Right now the site uses Jekyll and it still needs:
  - math to be incorporated
  - a nice layout
  - a way to have source files that can be converted to nice pdfs without too much work.

What else?

