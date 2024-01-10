---
title: "September - Delphi Debates"
date: "2022-09-19T09:43:23-07:00"
tags:
- 2022
image: DebateIcon.png
---

People develop strong opinions about things they do or believe and sometimes have a difficult time seeing another point of view. This certainly exists for politics and religion but is also strong in the technology sector. Whether you use Mac or Windows, Android or iPhone, C++ or Delphi, it's not hard to find heated discussions about what is the best or "right" choice.

Embarcadero is hosting a series of online discussions to weigh in on some of the hot topics in the Delphi programming language. [The first one](https://blogs.embarcadero.com/freeandnil-delphi-developer-debate) was whether to use the SysUtils procedure [`FreeAndNil`](https://docwiki.embarcadero.com/Libraries/Alexandria/en/System.SysUtils.FreeAndNil) or call `Free` explicitly on your objects. This is a long-standing debate with strong opinions on both sides. A quick internet search will reveal many arguments, [some from long ago](https://stackoverflow.com/questions/3159376/which-is-preferable-free-or-freeandnil), and [some more recent](http://www.delphimagazine.com/2020/06/05/magic-behind-freeandnil). Along with how you free an object is the question of if and how you should check to see if an object variable is nil or not--there wasn't as much disagreement over the use of [<code>Assigned()</code>](https://docwiki.embarcadero.com/Libraries/Alexandria/en/System.Assigned).

The next debate covered [With, Goto, &amp; Label](https://blogs.embarcadero.com/delphi-developer-debate-with-goto-label-sllides-and-replay). The webinar was a good discussion and revealed a surprising number still using [`goto`](https://docwiki.embarcadero.com/RADStudio/Alexandria/en/Goto) but again there were arguments both for and against all sides. The  are surprising results about the usage of these constructs. (After inheriting a project with a vast number of [`with`](https://docwiki.embarcadero.com/RADStudio/Alexandria/en/Declarations_and_Statements_(Delphi)#With_Statements) statements, I have some pretty strong feelings about this subject!) 

We'll dive into these topics, find out what others have said, and look at some code to see why you might want to choose one technique over the other--and when. We'll keep it light-hearted but hopefully learn some interesting things about the internals of Delphi in the process.

## PRESENTER ##

[**David Cornelius**](https://corneliusconcepts.tech/aboutme) is a full-time Delphi developer and has been programming since the 1980s.
