---
Generator: 'texi2html 1.82'
description: Untitled Document
distribution: global
keywords: Untitled Document
resource-type: document
title: Untitled Document
...

1. What Is Free Software? {#what-is-free-software .chapter}
=========================

### The Free Software Definition {#the-free-software-definition .subheading}

> The free software definition presents the criteria for whether a
> particular software program qualifies as free software. From time to
> time we revise this definition, to clarify it or to resolve questions
> about subtle issues. For a list of the changes we’ve made to the
> definition of free software, please see the “History” section,
> following the definition, at <http://gnu.org/philosophy/free-sw.html>.

“Free software” means software that respects users’ freedom and
community. Roughly, it means that **the users have the freedom to run,
copy, distribute, study, change and improve the software.** Thus, “free
software” is a matter of liberty, not price. To understand the concept,
you should think of “free” as in “free speech,” not as in “free beer.”
We sometimes call it “libre software” to show we do not mean it is
gratis.

We campaign for these freedoms because everyone deserves them. With
these freedoms, the users (both individually and collectively) control
the program and what it does for them. When users don’t control the
program, we call it a “nonfree” or “proprietary” program. The nonfree
program controls the users, and the developer controls the program; this
makes the program an instrument of unjust power.[(1)](#FOOT1)

@firstcopyingnotice{{@footnoterule@smallskip Copyright © 1996–2002,
2004–2007, 2009–2015 Free Software Foundation, Inc.\
 {The free software definition was first published in 1996, on
<http://gnu.org>. This version is part of @fsfsthreecite}

A program is free software if the program’s users have the four
essential freedoms:

-   The freedom to run the program as you wish, for any
    purpose (freedom 0).
-   The freedom to study how the program works, and change it so it does
    your computing as you wish (freedom 1). Access to the source code is
    a precondition for this.
-   The freedom to redistribute copies so you can help your
    neighbor (freedom 2).
-   The freedom to distribute copies of your modified versions to
    others (freedom 3). By doing this you can give the whole community a
    chance to benefit from your changes. Access to the source code is a
    precondition for this.

A program is free software if it gives users adequately all of these
freedoms. Otherwise, it is nonfree. While we can distinguish various
nonfree distribution schemes in terms of how far they fall short of
being free, we consider them all equally unethical.

In any given scenario, these freedoms must apply to whatever code we
plan to make use of, or lead others to make use of. For instance,
consider a program A which automatically launches a program B to handle
some cases. If we plan to distribute A as it stands, that implies users
will need B, so we need to judge whether both A and B are free. However,
if we plan to modify A so that it doesn’t use B, only A needs to be
free; we can ignore B.

The rest of this page clarifies certain points about what makes specific
freedoms adequate or not.

Freedom to distribute (freedoms 2 and 3) means you are free to
redistribute copies, either with or without modifications, either gratis
or charging a fee for distribution, to anyone anywhere. Being free to do
these things means (among other things) that you do not have to ask or
pay for permission to do so.

You should also have the freedom to make modifications and use them
privately in your own work or play, without even mentioning that they
exist. If you do publish your changes, you should not be required to
notify anyone in particular, or in any particular way.

The freedom to run the program means the freedom for any kind of person
or organization to use it on any kind of computer system, for any kind
of overall job and purpose, without being required to communicate about
it with the developer or any other specific entity. In this freedom, it
is the *user’s* purpose that matters, not the *developer’s* purpose; you
as a user are free to run the program for your purposes, and if you
distribute it to someone else, she is then free to run it for her
purposes, but you are not entitled to impose your purposes on her.

The freedom to run the program as you wish means that you are not
forbidden or stopped from doing so. It has nothing to do with what
functionality the program has, or whether it is useful for what you want
to do.

The freedom to redistribute copies must include binary or executable
forms of the program, as well as source code, for both modified and
unmodified versions. (Distributing programs in runnable form is
necessary for conveniently installable free operating systems.) It is OK
if there is no way to produce a binary or executable form for a certain
program (since some languages don’t support that feature), but you must
have the freedom to redistribute such forms should you find or develop a
way to make them.

In order for freedoms 1 and 3 (the freedom to make changes and the
freedom to publish the changed versions) to be meaningful, you must have
access to the source code of the program. Therefore, accessibility of
source code is a necessary condition for free software. Obfuscated
“source code” is not real source code and does not count as source code.

Freedom 1 includes the freedom to use your changed version in place of
the original. If the program is delivered in a product designed to run
someone else’s modified versions but refuse to run yours—a practice
known as “tivoization” or “lockdown,” or (in its practitioners’ perverse
terminology) as “secure boot”—freedom 1 becomes an empty pretense rather
than a practical reality. These binaries are not free software even if
the source code they are compiled from is free.

One important way to modify a program is by merging in available free
subroutines and modules. If the program’s license says that you cannot
merge in a suitably licensed existing module—for instance, if it
requires you to be the copyright holder of any code you add—then the
license is too restrictive to qualify as free.

Freedom 3 includes the freedom to release your modified versions as free
software. A free license may also permit other ways of releasing them;
in other words, it does not have to be a copyleft license. However, a
license that requires modified versions to be nonfree does not qualify
as a free license.

In order for these freedoms to be real, they must be permanent and
irrevocable as long as you do nothing wrong; if the developer of the
software has the power to revoke the license, or retroactively add
restrictions to its terms, without your doing anything wrong to give
cause, the software is not free.

However, certain kinds of rules about the manner of distributing free
software are acceptable, when they don’t conflict with the central
freedoms. For example, copyleft (very simply stated) is the rule that
when redistributing the program, you cannot add restrictions to deny
other people the central freedoms. This rule does not conflict with the
central freedoms; rather it protects them.

In the GNU Project, we use copyleft to protect the four freedoms legally
for everyone. We believe there are important reasons why it is better to
use copyleft. However, noncopylefted free software is ethical too. See
“Categories of Free Software” (@pageref{Categories}) for a description
of how “free software,” “copylefted software” and other categories of
software relate to each other.

“Free software” does not mean “noncommercial.” A free program must be
available for commercial use, commercial development, and commercial
distribution. Commercial development of free software is no longer
unusual; such free commercial software is very important. You may have
paid money to get copies of free software, or you may have obtained
copies at no charge. But regardless of how you got your copies, you
always have the freedom to copy and change the software, even to sell
copies.

Whether a change constitutes an improvement is a subjective matter. If
your right to modify a program is limited, in substance, to changes that
someone else considers an improvement, that program is not free.

However, rules about how to package a modified version are acceptable,
if they don’t substantively limit your freedom to release modified
versions, or your freedom to make and use modified versions privately.
Thus, it is acceptable for the license to require that you change the
name of the modified version, remove a logo, or identify your
modifications as yours. As long as these requirements are not so
burdensome that they effectively hamper you from releasing your changes,
they are acceptable; you’re already making other changes to the program,
so you won’t have trouble making a few more.

Rules that “if you make your version available in this way, you must
make it available in that way also” can be acceptable too, on the same
condition. An example of such an acceptable rule is one saying that if
you have distributed a modified version and a previous developer asks
for a copy of it, you must send one. (Note that such a rule still leaves
you the choice of whether to distribute your version at all.) Rules that
require release of source code to the users for versions that you put
into public use are also acceptable.

A special issue arises when a license requires changing the name by
which the program will be invoked from other programs. That effectively
hampers you from releasing your changed version so that it can replace
the original when invoked by those other programs. This sort of
requirement is acceptable only if there’s a suitable aliasing facility
that allows you to specify the original program’s name as an alias for
the modified version.

Sometimes government export control regulations and trade sanctions can
constrain your freedom to distribute copies of programs internationally.
Software developers do not have the power to eliminate or override these
restrictions, but what they can and must do is refuse to impose them as
conditions of use of the program. In this way, the restrictions will not
affect activities and people outside the jurisdictions of these
governments. Thus, free software licenses must not require obedience to
any nontrivial export regulations as a condition of exercising any of
the essential freedoms.

Merely mentioning the existence of export regulations, without making
them a condition of the license itself, is acceptable since it does not
restrict users. If an export regulation is actually trivial for free
software, then requiring it as a condition is not an actual problem;
however, it is a potential problem, since a later change in export law
could make the requirement nontrivial and thus render the software
nonfree.

A free license may not require compliance with the license of a nonfree
program. Thus, for instance, if a license requires you to comply with
the licenses of “all the programs you use,” in the case of a user that
runs nonfree programs this would require compliance with the licenses of
those nonfree programs; that makes the license nonfree.

It is acceptable for a free license to specify which jurisdiction’s law
applies, or where litigation must be done, or both.

Most free software licenses are based on copyright, and there are limits
on what kinds of requirements can be imposed through copyright. If a
copyright-based license respects freedom in the ways described above, it
is unlikely to have some other sort of problem that we never anticipated
(though this does happen occasionally). However, some free software
licenses are based on contracts, and contracts can impose a much larger
range of possible restrictions. That means there are many possible ways
such a license could be unacceptably restrictive and nonfree.

We can’t possibly list all the ways that might happen. If a
contract-based license restricts the user in an unusual way that
copyright-based licenses cannot, and which isn’t mentioned here as
legitimate, we will have to think about it, and we will probably
conclude it is nonfree.

When talking about free software, it is best to avoid using terms like
“give away” or “for free,” because those terms imply that the issue is
about price, not freedom. Some common terms such as “piracy” embody
opinions we hope you won’t endorse. See “Words to Avoid (or Use with
Care) Because They Are Loaded or Confusing” (@pageref{Words to Avoid})
for a discussion of these terms. We also have a list of proper
translations of “free software” into various languages
(@pageref{Appendix B}).

Finally, note that criteria such as those stated in this free software
definition require careful thought for their interpretation. To decide
whether a specific software license qualifies as a free software
license, we judge it based on these criteria to determine whether it
fits their spirit as well as the precise words. If a license includes
unconscionable restrictions, we reject it, even if we did not anticipate
the issue in these criteria. Sometimes a license requirement raises an
issue that calls for extensive thought, including discussions with a
lawyer, before we can decide if the requirement is acceptable. When we
reach a conclusion about a new issue, we often update these criteria to
make it easier to see why certain licenses do or don’t qualify.

If you are interested in whether a specific license qualifies as a free
software license, see our list of licenses, at
<http://gnu.org/licenses/license-list.html>. If the license you are
concerned with is not listed there, you can ask us about it by sending
us email at <licensing@gnu.org>.

If you are contemplating writing a new license, please contact the Free
Software Foundation first by writing to that address. The proliferation
of different free software licenses means increased work for users in
understanding the licenses; we may be able to help you find an existing
free software license that meets your needs.

If that isn’t possible, if you really need a new license, with our help
you can ensure that the license really is a free software license and
avoid various practical problems.

### Beyond Software {#beyond-software .subheading}

Software manuals must be free,[(2)](#FOOT2) for the same reasons that
software must be free, and because the manuals are in effect part of the
software.

The same arguments also make sense for other kinds of works of practical
use—that is to say, works that embody useful knowledge, such as
educational works and reference works. Wikipedia is the best-known
example.

Any kind of work *can* be free, and the definition of free software has
been extended to a definition of free cultural works[(3)](#FOOT3)
applicable to any kind of works.

### Open Source? {#open-source .subheading}

Another group users the term “open source” to mean something close (but
not identical) to “free software.” We prefer the term “free software”
because, once you have heard that it refers to freedom rather than
price, it calls to mind freedom. The word “open” never refers to
freedom.[(4)](#FOOT4)

<div class="footnote">

------------------------------------------------------------------------

### Footnotes

### [(1)](#DOCF1)

@raggedright See “Free Software Is Even More Important Now”
(@pageref{More Important Now}) for more on this issue. @end raggedright

### [(2)](#DOCF2)

@raggedright See “Why Free Software Needs Free Documentation”
(@pageref{Free Doc}). @end raggedright

### [(3)](#DOCF3)

@raggedright See <http://freedomdefined.org>. @end raggedright

### [(4)](#DOCF4)

@raggedright See “Why Open Source Misses the Point of Free Software”
(@pageref{OS Misses Point}). @end raggedright

</div>

------------------------------------------------------------------------

This document was generated by *tonghuix* on *March 25, 2016* using
[*texi2html 1.82*](http://www.nongnu.org/texi2html/).\
