---
layout: default
title: Book Chair Overview
updated: 16 dec 2018 by slukin

---

You are a Book Chair if you are a Workshop Chair, Demo Chair, Industry Chair, SRW Chair, Tutorial Chair, or Conference Publication Chair: You will put together a beautiful book to be printed and hosted on the [ACL Anthology](https://aclanthology.coli.uni-saarland.de/)! 

I'm a Book Chair, so what am I supposed to do?
===================================================

## Table of Contents

* [Responsibilities](#responsibilities)
* [The Process](#the-process)
* [Setting up the Final submission page to collect the Camera ready papers](#setting-up-the-final-submission-page-to-collect-the-camera-ready-papers)
* [Producing Proceedings](aclpub-start.md)
* [Authors](#authors)

Responsibilities
---------------
Produce the proceedings for your workshop or conference. Make sure they don't have any problems and look good.

The Process
---------------

1. Authors use the templates, provided by you, to create camera-ready papers.
   1. There's an FAQ for authors here, and feel free to add more: [camera-ready-faq.md](camera-ready-faq.md)
   
2. Remind authors: 
    1. The date the camera-ready papers are due
    2. Page limits for camera-ready papers
    3. The margin rulers and anonymization 
       can be removed by uncommenting the <code>\aclfinalcopy</code> 
       command near the top of the .tex file.
       
3. Set up the Final Submission Page on your Softconf website. 
   1. Your Softconf website is something like `https://www.softconf.com/naacl2019/SemEval`, with `naacl2019` replaced by the conference name and `SemEval` replaced by your volume name. This information should be provided to you by your conference publication chair.
   2. The Final Submission Page has several fields for uploading attachments. These have names like **Final Attachment - Software**. The type following the hyphen is significant; it will be displayed (after inserting spaces in the right places) on the ACL Anthology. Currently, the typical set of types is: `LaTeXSource`, `Software`, `Dataset`, and `Note`. If you want to use a different set of types, it would be good to discuss this with the ACL Anthology Editor.
   
4. Remind authors again of the camera-ready due date; preferably two weeks before, 1 week before, 3 days before, and 1 day before.

5. Authors upload camera-ready papers by logging into the submission page on START.

6. Once they've uploaded to START, now you:
    1. <a href="aclpub-start.md">Generate proceedings within START</a>
    2. Download the proceedings to see all issues
    3. Address any issues in START
    4. Repeat steps i-iii until the proceedings are good to go.
    
7.  Let the publication chairs know when you have finished. You do not need to email the finished tarball to them.

Email your conference publications chairs if you have questions about preparing your paper or proceedings.


Setting up the Final submission page to collect the Camera ready papers
---------------

Before you start collecting the camera-ready papers for your conference or workshop, you need to create a **Custom Final Submission Page**. To do that, you need to go in the _Manager Console_, then to the _Custom Submission Page Editor_ in your workshop's softconf account.

First of all, please check that a final page for your publication does not already exist. If you are running a workshop, in fact, it may be that the Softconf people already populated an ACLPUB final submission page for you.

If a final submission page is not yet available, please create one by clicking on the _New Page_ tab, using the "-- (ACLPUB Final Submission template) --". Please edit all the copyright information and the additional text as you wish. You may add additional textboxes, selectors, and the like to collect more information if needed.

When you are satisfied with the final submission page, you need to make it visible by activating it. To activate it, please go in the Manager Console, then _Visibility/Phasing/Deadlines_. Make the page the only one visible for **Revision**, and be sure to set a reasonable **deadline** for the page.

To test if the page works properly, you need to try it using the passcode of an accepted paper. To get the passcode, you can use the Spreadsheet Maker in the Manager Console.

Authors
---------------

This [git repository](https://github.com/acl-org/acl-pubs) 
is currenty maintained by the 2019 NAACL publications chairs, [Stephanie Lukin](https://users.soe.ucsc.edu/~slukin/) and Alla Rozovskaya.

The material
included in it has evolved over many years through the work of a 
large number of volunteers, including past NAACL and ACL publications chairs
Min-Yen Kan
[Stephanie Lukin](https://users.soe.ucsc.edu/~slukin/),
[Margaret Mitchell](http://www.m-mitchell.com/),
[Adam Lopez](http://homepages.inf.ed.ac.uk/alopez/),
[Matt Post](http://www.cs.jhu.edu/~post/),
[Colin Cherry](https://sites.google.com/site/colinacherry/),
[Nizar Habash](http://www.nizarhabash.com/),
[Claudia Leacock](https://www.linkedin.com/in/claudialeacockphd),
[Joakim Nivre](http://stp.lingfil.uu.se/~nivre/),
[Matt Post](http://www.cs.jhu.edu/~post/),
[Noah Smith](http://www.cs.cmu.edu/~nasmith/),
[William Schuler](https://www.ling.ohio-state.edu/~schuler/),
and
[Richard Wicentowski](http://www.cs.swarthmore.edu/~richardw/).


