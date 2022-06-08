# An Introduction and Tutorial for Common Lisp

> https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp.html

This document provides a small set of resources and references on Common Lisp. It was originally prepared for students in the Part-Time MS Program in Computer Science at the Johns Hopkins University. Most of this document was written 10+ years ago, since much of my time is now spent doing [Java and Ajax](https://web.archive.org/web/20131203162826/http://www.coreservlets.com/) work. Nevertheless, please send corrections/suggestions to [Marty Hall](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/) (hall@jhu.edu). The original of this document is at http://www.apl.jhu.edu/~hall/lisp.html. Also see the [Belorussian version of the tutorial](https://web.archive.org/web/20131203162826/http://www.fatcow.com/edu/lisp-be/), translated by Paul Bukhovko and provided by [fatcow](https://web.archive.org/web/20131203162826/http://www.fatcow.com/).

Note that some of the documents are in PostScript. If your WWW browser cannot display PostScript, they can still be saved and printed.

## Table of Contents	

- [Lisp-Related Books.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp.html#Books)
- [Online Lisp References.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp.html#Section1)
- [Issues for Lisp Beginners and Advanced Beginners.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp.html#Section2)
- [Issues for Intermediate/Advanced Lisp Programmers.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp.html#Section3)
- [CLOS.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp.html#Section4)
- [Internet Lisp Resources and Free Lisp Implementations.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp.html#Section5)
- [Lisp-Related Papers.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp.html#Section6)
- [Misc.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp.html#Section7)

## Lisp-Related Books

Here are some of my personal favorite Lisp, AI Programming, and general AI texts. **I can recommend all of them from personal experience.** Click on the titles to see more information or to order them on-line.

- Basic Common Lisp Programming
  - No AI Slant: Moderately Fast-Paced: [*ANSI Common Lisp* by Paul Graham](https://web.archive.org/web/20131203162826/http://www.amazon.com/exec/obidos/ISBN=0133708756/martyhallsrecomm/). The best introduction to Common Lisp as a general-purpose programming language. A bit hard going for inexperienced programmers, however.
  - AI Slant: [*Lisp* by Winston and Horn](https://web.archive.org/web/20131203162826/http://www.amazon.com/exec/obidos/ISBN=0201083191/martyhallsrecomm/). The classic AI applications in Lisp text.
- Advanced Common Lisp Programming
  - No AI Slant: [*On Lisp: Advanced Techniques for Common Lisp* by Paul Graham](https://web.archive.org/web/20131203162826/http://www.amazon.com/exec/obidos/ISBN=0130305529/martyhallsrecomm/). Amazingly deep coverage of macros and closures.
  - AI Slant: [*Paradigms of AI Programming: Case Studies in Common Lisp* by Peter Norvig](https://web.archive.org/web/20131203162826/http://www.amazon.com/exec/obidos/ISBN=1558601910/martyhallsrecomm/). My single all-time favorite Common Lisp text.
- CLOS
  - [*Object Oriented Programming in Common Lisp: A Programmers Guide to the Common Lisp Object System* by Sonya Keene.](https://web.archive.org/web/20131203162826/http://www.amazon.com/exec/obidos/ISBN=0201175894/martyhallsrecomm/)
- Lisp References
  - [*Common Lisp: The Language* by Guy L. Steele Jr.](https://web.archive.org/web/20131203162826/http://www.amazon.com/exec/obidos/ISBN=1555580416/martyhallsrecomm/) The definitive reference prior to the release of the ANSI spec. Look up "kludges" in the index for some good geek humor. My other favorite is the "BOA constructor" business.
- Scheme (really programming and algorithms)
  - [*Structure and Interpretation of Computer Programs* by Abelson, Sussman, and Sussman](https://web.archive.org/web/20131203162826/http://www.amazon.com/exec/obidos/ISBN=0262011530/martyhallsrecomm/). One of **the** best Computer Science texts I've ever seen. More good stuff in the footnotes than in the entire contents of most other books.
- Artificial Intelligence (roughly in order of preference)
  - [*Artificial Intelligence: A Modern Approach* by Russell and Norvig](https://web.archive.org/web/20131203162826/http://www.amazon.com/exec/obidos/ISBN=0131038052/martyhallsrecomm/). If I had to pick one AI text, this would be it.
  - [*Essentials of Artificial Intelligence* by Matt Ginsberg](https://web.archive.org/web/20131203162826/http://www.amazon.com/exec/obidos/ISBN=1558602216/martyhallsrecomm/). Entertaining and concise introduction to the best-established areas of AI.
  - [*Artificial Intelligence Theory and Practice* by Dean, Allen, and Aloimonos](https://web.archive.org/web/20131203162826/http://www.amazon.com/exec/obidos/ISBN=0805325476/martyhallsrecommA/). A good AI book that includes some coverage of (and examples in) Common Lisp.
  - [*Artificial Intelligence: Structures and Strategies for Complex Problem Solving* by Luger and Stubblefield](https://web.archive.org/web/20131203162826/http://www.amazon.com/exec/obidos/ISBN=0805347801/martyhallsrecommA/). If you want a good AI book that includes some coverage of Lisp **and** Prolog, this is the one for you.
  - [*Artificial Intelligence* by Patrick Henry Winston](https://web.archive.org/web/20131203162826/http://www.amazon.com/exec/obidos/ISBN=0201533774/martyhallsrecomm/). The classic reference. A bit heavy on the topic of learning.

- Java and Web Programming.

  OK, ok, so these don't have anything to do with Lisp. But I couldn't resist.

  - [Recommended books on Java, Ajax, JavaScript, and Web programming.](https://web.archive.org/web/20131203162826/http://resources.coreservlets.com/java-ee-books.html)

## Online Lisp References

- HyperSpec. An HTML version of the official ANSI specification for Common Lisp. From Kent Pitman and Harlequin Inc. Not a tutorial, but completely defines *every* function, variable, and construct all of Common Lisp.

  - [Table of Contents.](https://web.archive.org/web/20131203162826/http://www.harlequin.com/books/HyperSpec/FrontMatter/Chapter-Index.html)
  - [Highlights (alternate Table of Contents).](https://web.archive.org/web/20131203162826/http://www.harlequin.com/books/HyperSpec/FrontMatter/Highlights.html)
  - [Master Index.](https://web.archive.org/web/20131203162826/http://www.harlequin.com/books/HyperSpec/FrontMatter/Master-Index.html)
  - [Index of all words in Common Lisp (variables, function names, etc).](https://web.archive.org/web/20131203162826/http://www.harlequin.com/books/HyperSpec/FrontMatter/Symbol-Index-Alphabetical.html)
  
- Common Lisp: The Language (2nd Edition, HTML version). This was the official language definition prior to the release of the ANSI Specification, and is still a useful reference.

  - [Table of Contents.](https://web.archive.org/web/20131203162826/http://www.cs.cmu.edu/Web/Groups/AI/html/cltl/clm/node1.html)
- [Index.](https://web.archive.org/web/20131203162826/http://www.cs.cmu.edu/Web/Groups/AI/html/cltl/clm/)
  - [Intro/Overview.](https://web.archive.org/web/20131203162826/http://www.cs.cmu.edu/Web/Groups/AI/html/cltl/cltl2.html)

- [The draft ANSI specification for Common Lisp (PostScript by sections).](https://web.archive.org/web/20131203162826/http://www.stat.ucla.edu:80/develop/lisp/common/docs/ansi/index.html) For online access, use the [HyperSpec.](https://web.archive.org/web/20131203162826/http://www.harlequin.com/books/HyperSpec/FrontMatter/Starting-Points.html), but the final ANSI spec is not available free in PostScript.

- [On-line guide to the CLOS MOP (Meta-Object Protocol).](https://web.archive.org/web/20131203162826/http://www.elwoodcorp.com/alu/mop/contents.html)

- [How to access *Common Lisp: The Reference* from the local machine](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/clman.html) (apl.jhu.edu users only).

- [User's Guide for CLIM 2.0.](https://web.archive.org/web/20131203162826/http://www.harlequin.com/common-lisp/clim2/) CLIM is the *Common Lisp Interface Manager*, a graphics library supported by several different vendors. User's Guide is from Harlequin.

- [A short bibliography of Lisp references.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Lisp-References.html) Also available [in PostScript.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Lisp-References.ps)

## Issues for Lisp Beginners and Advanced Beginners

- [A one-page summary of the most basic Lisp constructs (PostScript).](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Introductory-Lisp-Overview.ps)
- Some thumbnail summaries. The PostScript versions are one page.
  - [When to use or not use **quote**.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/Lisp-Quote-Hints.text)
  - [**cond**, **let**, and **let\***.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Cond+Let.html) Also available [in PostScript with brief **loop** info on same page.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Cond+Let.ps)
  - [**loop**.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Loop-Summary.html) Also available [in PostScript.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Loop-Summary.ps)
  - [**format**, Lisp's answer to C's **fprintf**.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Format.html) Also available [in PostScript.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Format.ps)
  - [Structures and **defstruct** syntax.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Structures.html) Also available [in PostScript.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Structures.ps)
  - [**backquote** (PostScript).](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Backquote.ps)
  - [CLOS.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/CLOS-Summary.html) Also available [in PostScript.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/CLOS-Summary.ps)
- [Very brief summary of how to interact with Lisp from within emacs.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Emacs-Lisp-Interaction.text) See the PostScript emacs handouts ([Quick Reference Sheet](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/text/Emacs-Quick-Reference.ps) and [Intro](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/text/Emacs-Intro.ps)) for more details.
- [Slightly more detailed summary of how to interact with Lisp from within XEmacs and GNU Emacs, under X-Windows or on dumb terminals.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Emacs-Lisp-Interaction2.text) See the PostScript emacs handouts ([Quick Reference Sheet](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/text/Emacs-Quick-Reference.ps) and [Intro](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/text/Emacs-Intro.ps)) for more details.
- [Even briefer summary of using vi for Lisp. How to blink parens and do auto-indentation.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/VI-Settings.text)
- [Capturing the results of an interactive Lisp session.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/Capturing-Output.text) I.e. how to save the results of testing to file. This gives Lisp-specific (**dribble**), UNIX-specific (**script**), and emacs-specific methods. In all cases, use of the [**Show-Output** macro](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/Show-Output.lisp) will make it easier to save the test cases.
- [The convention of putting "*"s around global variable names in Lisp.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Naming-Globals.text)
- [A simple Common Lisp implementation of Towers of Hanoi.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/Hanoi.lisp)
- [A Common Lisp implementation of the N-Queens problem.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/N-Queens.lisp) Finds a solution to the N-Queens problem for any N 4 or greater. The solution can be found in linear time (constant time per queen), although printing out the board takes O(N^2) time. But no search is involved. If you have a Java enabled browser, visit [http://www.apl.jhu.edu/~hall/NQueens.html](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/NQueens.html) to see an interactive version of this in Java.
- [A very brief example of using the Common Lisp **sort** function.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Sort.text)

## Issues for Intermediate/Advanced Lisp Programmers

- [An introduction to some higher-order Common Lisp functions.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Higher-Order.html) Higher-order functions are ones that use other functions as arguments. Passing functions around in Lisp is one of its distinctive features. Also available [in PostScript.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Higher-Order.ps)
- [A macro called **Show-Output** that lets you save test cases. ](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/Show-Output.lisp)*Using* Show-Output is not at all difficult: you just supply Lisp forms and each form is printed out along with the return value of the form. But *writing* it requires a basic understanding of Lisp macros.
- [Some hints on benchmarking Lisp code (PostScript).](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Benchmarking-Hints.ps)
- [A set of simple timing/metering functions in Common Lisp.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/Simple-Metering.lisp)
- [Destructive operations and list performance.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Destructive-Ops.html) Also available [in PostScript.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Destructive-Ops.ps)
- [An introduction to Common Lisp macros.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Macros.html) Macros are forms that generate Lisp code. Also available [in PostScript.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Macros.ps)
- [Guide to good Lisp style (PostScript).](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Good-Lisp-Style.ps) From Peter Norvig and Kent Pittman's LUV-93 tutorial.
- [Jeff Dalton's list of Common Lisp pitfalls.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Dalton-Pitfalls-List.text) Most are for the advanced user.
- [VT100 cursor control from Lisp.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/VT100.lisp)
- [A Short Ballad Dedicated to the Growth of Programs (by Ashwin Ram).](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/Scheme-Ballad.text)

## CLOS

CLOS is the "Common Lisp Object System", a powerful OOP package built into Common Lisp.

- [A thumbnail summary of CLOS.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/AI-Programming/CLOS-Summary.html) Also available as [a one-page PostScript file.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/CLOS-Summary.ps)

- [Introductory CLOS lecture notes.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/AI-Programming/CLOS.html) Also available [in PostScript.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/CLOS.ps)

- [Common CLOS Blunders (PostScript).](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Common-CLOS-Blunders.ps)

- [Some details on **defclass**.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Defclass.html) Also available [in PostScript.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Defclass.ps)

- [Some details on **defgeneric**.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Defgeneric.html) Also available [in PostScript.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Defgeneric.ps)

- A simplified interface to **defclass**. The **Def-Class** macro lets you type

  ```commonlisp
  (Def-Class Class (Parents)
    (Slot-1 Val-1)
    (Slot-2 Val-2)
    Slot-3)
  ```
  
  and get the effect of
  
  ```commonlisp
  (defclass Class (Parents)
    ((Slot-1 :initform Val-1 :accessor Slot-1 :initarg :Slot-1)
     (Slot-2 :initform Val-2 :accessor Slot-2 :initarg :Slot-2)
     (Slot-3                 :accessor Slot-3 :initarg :Slot-3)))
  ```
  
  The **Define-Class** macro has identical syntax to **Def-Class**, but it also adds a unique name slot and does some bookkeeping to keep track of instances. It supports **Instances** to get objects of the given class, **Direct-Instances** to get objects of the given class but not of a subclass, and several other bookkeeping routines.
  
- [*Optimizations in the Symbolics CLOS Implementations.*](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/text/Papers/CLOS-Optimizations.text) A paper by D. Scott Cyphers and David Moon showing how CLOS could be implemented efficiently.

## Internet Lisp Resources

- [A free Common Lisp for Windows.](https://web.archive.org/web/20131203162826/http://www.franz.com/downloads/#acl) This is a version of the popular commercial Allegro Common Lisp for Windows, with some limitations such as limited heap size, no foreign function support, no **compile-file**, no disassembler, and no image saving (save-image). However, **compile** is still available and files get compiled as they are loaded (you just can't save the compiled version to disk). Otherwise this is the same version as their commercial implementation. An excellent choice for students with Windows machines at home, and includes an interactive tutorial. This page also allows downloading of a free evaluation copy of Allegro CL for UNIX. Also see [the Franz Web Site](https://web.archive.org/web/20131203162826/http://www.franz.com/) for more info on this offering.
- [Another free Common Lisp for Windows.](https://web.archive.org/web/20131203162826/http://www.harlequin.com/freelisp/) From [Harlequin, Inc.](https://web.archive.org/web/20131203162826/http://www.harlequin.com/), makers of the UNIX LispWorks environment, this is a more limited implementation formerly only for academic use. No compiler.
- [A limited-time use evaluation copy of Macintosh Common Lisp 4.0.](https://web.archive.org/web/20131203162826/http://www.digitool.com/MCL-demo-version.html) From Digitool.
- [Pointers to other free Common Lisps available on the Net for UNIX, VMS, DOS/Windows, and Macintosh.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/Free-Common-Lisps.text) Extracted from version 1.48 of the [FAQ for comp.lang.lisp.](https://web.archive.org/web/20131203162826/http://www.cs.cmu.edu/Web/Groups/AI/html/faqs/lang/lisp/top.html) See there for the latest details.
- [Lecture notes, handouts, and some exercises from Marty Hall's AI Programming class in the Hopkins part-time MS program in CS.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/AI-Programming)
- [The Association of Lisp Users (ALU).](https://web.archive.org/web/20131203162826/http://www.elwood.com/alu/table/contents.htm)
- [Tulane's Interactive Lisp Tutorial.](https://web.archive.org/web/20131203162826/http://www.cs.tulane.edu/www/Villamil/lisp/lisp1.html) By Eduardo Villamil.
- [Texas A&M; Basic Lisp Tutorial.](https://web.archive.org/web/20131203162826/http://grimpeur.tamu.edu/~colin/lp/) By Colin Allen and Maneesh Dhagat.
- [The FAQ (Frequently Asked Questions) list from comp.lang.lisp.](https://web.archive.org/web/20131203162826/http://www.cs.cmu.edu/Web/Groups/AI/html/faqs/lang/lisp/top.html)
- [CMU's Archive of Common Lisp Code.](https://web.archive.org/web/20131203162826/http://www.cs.cmu.edu/afs/cs.cmu.edu/project/ai-repository/ai/lang/lisp/0.html)
- [Lisp Resources Page from the WWW Virtual Library.](https://web.archive.org/web/20131203162826/http://eksl-www.cs.umass.edu/lisp-resources.html)
- Source Code from Three Popular Common Lisp Texts.
  - [Paul Graham's *ANSI Common Lisp*.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/Graham/acl-examples.lisp)
  - [Paul Graham's *On Lisp: Advanced Techniques for Common Lisp*.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/Graham/onlisp.lisp)
  - [Peter Norvig's *Paradigms of Artificial Intelligence Programming: Case Studies in Common Lisp*.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/Norvig/)
- [An extensible http server written in Common Lisp.](https://web.archive.org/web/20131203162826/http://www.ai.mit.edu/projects/iiip/doc/cl-http/home-page.html) From the [MIT AI Lab.](https://web.archive.org/web/20131203162826/http://www.ai.mit.edu/)
- [A commercial ANSI-CL to C translator and Lisp-in-C libraries.](https://web.archive.org/web/20131203162826/http://www.elwoodcorp.com/eclipse.htm)
- [The comp.lang.lisp Usenet newsgroup.](https://web.archive.org/web/20131203162826/news:comp.lang.lisp) You may want to use a newsreader like nn or gnus instead of a WWW browser if you really subscribe to it.
- [Collection of job postings for Lisp-related positions.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/Lisp-Notes/Lisp-Jobs.mailbox) Most of these jobs come from [the Lisp-Jobs mailing list of Mark Kantrowitz](https://web.archive.org/web/20131203162826/mailto:ai+query@cs.cmu.edu) (send "help" in the body) or the [comp.lang.lisp](https://web.archive.org/web/20131203162826/news:comp.lang.lisp) Usenet group. This collection is in UNIX mailbox format, so to peruse you probably want to download it and read it with your favorite mailreader. It also includes AI-related jobs that don't necessarily mention Lisp if they are in the greater Baltimore/Washington area. For complete archives of the Lisp-Jobs and AI-Jobs mailing lists, see [the archives at CMU.](https://web.archive.org/web/20131203162826/http://www.cs.cmu.edu/afs/cs.cmu.edu/Web/Groups/AI/jobs/)

## Lisp-Related Papers

- [A Brief History of Lisp.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/text/Papers/Brief-History-of-Lisp.ps) (PostScript)
- [The Evolution of Lisp](https://web.archive.org/web/20131203162826/http://www.dreamsongs.com/NewFiles/Hopl2.pdf) A Detailed History of Lisp, from the 1993 ACM History of of Programming Languages (*HOPL-II*) conference. (PDF)
- [Lisp: Good News, Bad News, How to Win Big.](https://web.archive.org/web/20131203162826/http://www.ai.mit.edu/articles/good-news/good-news.html) From *AI Expert*. Also available [in PostScript.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/text/Papers/Lisp-Good-News-Bad-News.ps)
- Hall, Marty and James Mayfield, ["Improving the Performance of AI Software: Payoffs and Pitfalls in Using Automatic Memoization,"](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/text/Papers/Monterrey-Memoization.ps) *Procedings of Sixth International Symposium on Artificial Intelligence*, Monterrey, Mexico, September 1993. (PostScript). Source code is available [here.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/Memoization) See the top of [Memoization.lisp](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/lisp/Memoization/Memoization.lisp) for a quick description of the main user-level functions.
- [Paper by Ken Anderson giving details of numeric optimization in Lisp with comparisons to C.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/text/Papers/Lisp-Benchmarking-and-Fannkuch.ps) Based around an algorithm known as *fannkuch*. (PostScript)
- [Henry Baker's outstanding collection of Lisp-related papers.](https://web.archive.org/web/20131203162826/ftp://ftp.netcom.com/pub/hb/hbaker/home.html) Note that netcom is frequently overloaded, so it might take several tries to connect.
- [A survey of garbage collection techniques by Paul Wilson.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/text/Papers/Bigger-GC-Survey.ps) To appear in ACM's *Computing Surveys*. (PostScript)
- [Garbage Collection FAQ maintained by David Chase of Centerline.](https://web.archive.org/web/20131203162826/http://www.centerline.com/people/chase/GC/GC-faq.html)
- GC Papers by Hans-J Boehm at Xerox PARC:
  - [Discussion on the complexity of mark-sweep vs. copying garbage collectors.](https://web.archive.org/web/20131203162826/ftp://parcftp.xerox.com/pub/gc/complexity.html) He attempts to refute the claims that copying collectors have better paging performance due to compaction, and that the asymptotic time complexity of copying collectors is necessarily better.
  - [Example showing that in some cases explicit allocation/deallocation (malloc/free) can be computationally more expensive than garbage collection.](https://web.archive.org/web/20131203162826/ftp://parcftp.xerox.com/pub/gc/example.html) Note that he is not claiming that GC is faster in practice, only refuting the claim that it *must* be slower.
  - [A garbage collector for C and C++.](https://web.archive.org/web/20131203162826/ftp://parcftp.xerox.com/pub/gc/gc.html)

## Misc.

- [Home Page for Marty Hall.](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/)
- [Java programming tutorial.](https://web.archive.org/web/20131203162826/http://courses.coreservlets.com/Course-Materials/java5.html)
- [Servlet and JSP tutorial](https://web.archive.org/web/20131203162826/http://courses.coreservlets.com/Course-Materials/csajsp2.html)
- [Apache Tomcat tutorial.](https://web.archive.org/web/20131203162826/http://www.coreservlets.com/Apache-Tomcat-Tutorial/tomcat-7-with-eclipse.html)
- [JSF 2.0 tutorial.](https://web.archive.org/web/20131203162826/http://www.coreservlets.com/JSF-Tutorial/jsf2/)
- [Ajax and jQuery tutorial.](https://web.archive.org/web/20131203162826/http://courses.coreservlets.com/Course-Materials/ajax.html) See also the section on [JavaScript programming](https://web.archive.org/web/20131203162826/http://courses.coreservlets.com/Course-Materials/ajax-basics.html) that has many functional programming and Lisp-related concepts.
- [GWT tutorial.](https://web.archive.org/web/20131203162826/http://courses.coreservlets.com/Course-Materials/gwt.html)
- [Customized onsite training courses: Java, JSF 2.0, servlets, JSP, Ajax, jQuery, GWT, Spring, Hibernate, etc.](https://web.archive.org/web/20131203162826/http://courses.coreservlets.com/)
- [Java Programming Resources at Johns Hopkins](https://web.archive.org/web/20131203162826/http://www.apl.jhu.edu/~hall/java/)