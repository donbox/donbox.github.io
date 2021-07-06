---
layout: default
title: "My writing tools"
description: "Optimizing the path from my brain to storage."
---

# My Writing Tools

December 2020 kicked off a real creative period for me.

I'm programming more than I have in over a decade.  I joined a [Guitar Circle](https://en.wikipedia.org/wiki/Guitar_Craft) and am learning to play in [New Standard Tuning](https://en.wikipedia.org/wiki/New_standard_tuning) - with a pick no less. And as always, I'm using writing and teaching as a way to increase my understanding and insight, so I'm writing prose a lot.

I'm working way differently than in the past, and thought I'd catalog my digital toolset journey here, mainly for the personal perspective I get out of writing stuff down.

## TL;DR

I live in VS Code, writing Rust and/or Markdown for pretty much everything. It's pretty sweet.  The rest of page is all historical.

## Editing Text

The first text editor I fell in love with was [MPW Shell](https://en.wikipedia.org/wiki/Macintosh_Programmer%27s_Workshop).  I was doing free lance Mac programming in C++ and HyperCard to pay the bills, and this is where I started.  I loved the way the shell and editor integrated - [Cmd-Enter](http://mirror.informatimago.com/next/developer.apple.com/tools/mpw-tools/commandref/doit.html) was mind-blowing! 

When I hit grad school, I started using Sun workstations and NeXT cubes, so I picked up [GNU Emacs](http://www.gnu.org/software/emacs/) as my primary editor, as it was everywhere I needed to be.  

I lived in emacs throughout grad school and for about a decade afterwards. It was my source code editor, my shell, and my email system.  I really loved it.

Any time I found myself doing things outside of emacs, I had the feeling that I wasn't quite smart enough to do the task properly or efficiently.  More on this later.

I stayed with emacs after I started working at Microsoft, to the point where I gave a keynote at the 2003 [Microsoft's Professional Developer's Conference](https://en.wikipedia.org/wiki/Professional_Developers_Conference) (the //build of the 1990's and 2000's) using only emacs (no PowerPoint, no Visual Studio). 

When Visual Studio 2005 (a.k.a., Whidbey) was in development, I opted to start using VS as my primary editor. Some people on the team really wanted me to dogfood and give my unabashed feedback, so I did it.  The tool got to be good enough to become my daily driver, and I spent used VS 2005 untl about 2007.  

By 2007, I was on a project called [Oslo](https://www.developer.com/design/building-microsoft-oslo-models/), and we built a new text editor (Intellipad/ipad.exe) and IDE (Quadrant) based on a fork of the in-development VS editor rewrite.  Naturally, I switched to the Oslo tools and lived in them until the project's [demise in 2010](https://www.zdnet.com/article/microsoft-oslo-modeling-platform-unravels-further-ms-future-remains-vague/).

After that, I reverted back to emacs (but had long since lost my precious [~/.emacs file](https://www.gnu.org/software/emacs/manual/html_node/emacs/Init-File.html).

Like a lot of of the world, I switched to [VS Code](https://code.visualstudio.com) a few years ago.  I'm really hoping this is the last editor I need to adapt to - both because I love it, and honestly, the switching cost is pretty high for me.



## Creating and Publishing Prose

Earlier I mentioned that I felt slightly inadequate when I had to leave emacs to get things done. The most conspicuous place where I failed to live up to the emacs ideal was when it came to authoring documents and presentations.

Being a Mac person, I couldn't fathom having to use a compiler and asynchronous previewer to work on papers ([LaTeX](https://www.latex-project.org)) or slides ([SliTeX](https://nwalsh.com/tex/texhelp/SliTeX.html)).  I managed to get a few papers authored in FrameMaker published into refereed journals/conferences.  

Once I left grad school and switched to publishing books, articles, and columns. I found that Microsoft Word was good enough, and it became my primary way to get paragraphs out of my head and into digital storage up until very recently.  The publication part was pretty straightforward. I'd email Word documents to my editor, they'd send back either post-layout PDFs (MSJ and MSDN), proofs and [F&G's](https://www.printindustry.com/Newsletters/Newsletter-109.aspx)(Addison Wesley), or plain-old-text comments (C++ Report).

I pretty much stopped the book/article/column routine when I started working at Microsoft in 2002. My day job at the time was working on Microsoft's SOAP implementation, which grew out of an early collaboration with [Dave Winer](http://scripting.com), Mohsen Agsen, and Bob Atkinson. Dave also was an early pioneer in [RSS](https://cyber.harvard.edu/rss/rss.html) and [blogging](https://en.wikipedia.org/wiki/Blog), both of which were heating up at the time.  

I got interested in how RSS was building momentum (while SOAP well...wasn't). I also missed writing, so I decided to stand up a blog to try to internalize what was going on.
My dear friend Sara Williams (nee Spalding) from the .NET Framework team let me set up a static directory on the now defunct gotdotnet.com server, and presto, Microsoft had it's first public blog (about a year before Robert Scoble became an MS employee and got techfamous as a blogger). 

That first blog was authored as a ginormous XML file, and the HTML, RSS, and later AtomPub projections were done in [XSLT](https://www.w3.org/TR/1999/REC-xslt-19991116).  IIRC, "publishing" was just updating my content.xml file over SMB, and the XSLT's ran either as an IIS filter or via the `xml-stylesheet` processing instruction.  It was pretty sweet.

When [PluralSight](https://www.pluralsight.com) got started by a few friends/former coworkers, I moved my blog to their site using an off-the-shelf blog engine. The writing experience was *meh* but I was happy to be working with [Aaron](https://www.instagram.com/skonnard/), [Keith](https://www.pluralsight.com/authors/keith-brown), and [Fritz](https://www.instagram.com/fritzonion/) so it was all good.

About a year ago, I started writing primarily in markdown using VS Code.  The syntax is easy on the eye and the fingers, and I'm hoping this is the last format I need to master. 

In terms of publishing, I'm using [jekyll](https://jekyllrb.com) to generate this site, which is backed by a simple github repo.  It's quite sweet actually. 

## Creating and Publishing Slides

I gave my very first presentation in 1986 (my first year in grad school) as part of a funding pitch our group was making.

I wrote it on my Mac in Dave Winer's [More](https://en.wikipedia.org/wiki/MORE_(application)), and printed it out on transparency film (what Intel people refer to as *foils*).  Horrible talk, horrible tech, but More was pretty nice.

Like the rest of the world, I adopted PowerPoint and wrote way too many conference talks and courses in it.

Around the time I got to Microsoft, I had largely moved to giving talks in text editors, which is still how I like to work.

Recently, I discovered [Marp](https://marp.app), which allows me to author in Markdown, and present in formatted form from a preview window inside of VS Code. 

## Creating and Publishing Music Manuscripts

I haven't composed new music for a very long time, but I love transcribing music, primarily to really understand a how a piece of music holds together.

For many years, I would do the annual "which sucks less - [Finale](https://en.wikipedia.org/wiki/Finale_(scorewriter)) or [Sebelius](https://en.wikipedia.org/wiki/Sibelius_(scorewriter))" test during the holidays. Until very recently, Finale came out ahead, primarily due to the fact that it supported Chord Symbol playback, which comes in really handy for lead sheets.

A few months before COVID hit, my piano teacher turned me on to [Musescore](https://musescore.org/en), which has my pet Finale feature AND is a much better input medium.  Finale does a better job at printing, but not enough to warrant me continuing to use it.

In 2020, my test took a very different form. I spent my holiday break learning Rust by writing a domain specific langauge and compiler for music notation. The upside of this approach is that I can use VS Code as my authoring format (which is ideal for me), and I can write backends to whatever I need to publish to (primarily ultimate-guitar.com or iRealPro). Alas, I think it's going to take the next holiday break before it's good enough to use as my daily driver.

## Timelines

|Text Editor | Start Date | End Date |
| --- | --- | --- |
| Macintosh Programmer's Workbench | ~1986 | 1990 |
| GNU Emacs | 1988 | 2004 |
| Visual Studio 2005/2008 | 2004 | 2007 |
| Intellipad/Quadrant | 2007 | 2010 |
| GNU Emacs | 2010 | 2015 |
| VS Code | 2015 | - |

I'm hoping that VS Code is the last text tool I need to master, at least until EMG takes off.


| Document Format | Process | Start Date | End Date |
| --- | --- | --- | --- |
| FrameMaker | Submit via snail-mail or PDF's through FTP | 1987 | 1992 |
| Microsoft Word |Email to editor/publisher |  1992 | 2003 | 
| XML | Edit in Emacs over SMB, publish via IIS and XSLT | 2003 | 2004 |
| The other .NET-based engine (not DasBlog) | Browser-based editor | 2004 | ~2008 |
| Markdown | Edit against Github et al, publish via Jekyll or project-specific doc toolchains | 2017 | - |

I think Markdown is here to stay. I'm already finding myself working in non-Git repos, so I've resigned myself to not caring on this one.  Jekyll is new (and I'm new to it), but my needs are modest. 


| Presentation Format | Process | Start Date | End Date |
| --- | --- | --- | --- |
|  More | Print transparencies | 1988 | 1992 |
|  Microsoft PowerPoint | Projectors using VGA/DP/HDMI | 1992 | 2003 | 
| Ad hoc plain text and code | Projectors using VGA/DP/HDMI or Miracast (when it worked) | 2003 | 2020 | 
| Markdown | Edit against Github et al, present via Marp preview over Microsoft Teams | 2020 | 2020 |
| Markdown | Edit against Github et al, present via Marp preview over the rest of the world's video conferencing systems  | 2021 | - |

Again, I think Markdown is here to stay, and again, Marp meets my modest needs.

I will say that I miss the ubiquity of Microsoft Teams since I've left MS. I now find myself using 5 different VC solutions in a given week - none of which are Teams. Sigh...



## My Writing Rig

![My rig](/assets/2021/2021-07-04-my-work-env.jpg)







