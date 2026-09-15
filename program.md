---
layout: page
title: Program
---

<!-- 
<p style="color:red; font-style: italic;">CAUTION: THIS IS A PREVIEW AND THINGS ARE NOT FINAL YET</p>
 -->

* __Start:__ Monday 28 September 2026, in the morning
* __Finish:__ Friday 2 October 2026, in the afternoon


## Schedule
We will open with a meeting on Monday morning to coordinate plans for the week,
and follow a pattern of "stand-ups" each day at around 9:00, to
communicate what we plan to work on, and what we have worked on.
In the mornings there will be canapés; coffee and snacks will be available throughout the day.

This schedule is subject to change. 

Please note that these GAP Days will be in-person only.


- **Monday**
  - 10:00 Welcome and opening
  - 10:30 Kick-off: visualisation
  - 12:00 *Lunch break*
  - 13:30 Work Session
  - 17:00 End of first day

- **Tuesday**
  -  9:00 Breakfast & Stand-up round
  -  9:30 Work session
  - 11:00 Talk: **Fusion systems on groups of order $2^{10}$** (Pete Gautam)
  - 11:30 Work session
  - 12:20 Group photo
  - 12:30 *Lunch break*
  - 14:00 Talk: **Twisted Conjugacy: a computational perspective** (Sam Tertooy)
  - 14:30 Work session
  - 17:00 End of the day

- **Wednesday**
  -  9:00 Breakfast & Stand-up round
  -  9:30 Work session
  - 11:00 Talk: **NoFoMa - Normal forms of matrices** (Alia Bonnet)
  - 11:30 Work session
  - 12:30 *Lunch break*
  - 14:00 Discussion: "Getting help in GAP"
  - 15:30 Work session
  - 17:00 End of the day

- **Thursday**
  -  9:00 Breakfast & Stand-up round
  -  9:30 Work session
  - 12:30 *Lunch break*
  - 14:00 Work session
  - 17:00 End of the day
  - Conference dinner

- **Friday**
  -  9:00 Breakfast & Stand-up round
  -  9:30 Work session
  - 12:00 Closing session
  - 12:30 *Lunch break*


## Topics

As always, GAP Days are a chance to meet people, form connections, get help
with your problems, listen to some nice talks, and so on.

But in addition, we plan to focus on a few topics.

### Central topic: Visualisation

During these GAPDays we will focus on improving the visualisation of objects
created in GAP. During the last two GAP Days, this topic came up in many
discussions and now the goal is to get stuff done.

The plan is to create a visualisation package that other packages can use,
instead of rolling their own visualisation code again and again.

Moreover, we intend to work with package maintainers on switching their
package to use the new visualisation package. 

Everyone can contribute to this project by
- contributing code to the new visualisation package,
- contributing concrete ideas on additional visualisation options,
- working on packages to use the new tools (this can be your own package; or a package you simply use and would like to contribute to).

Regarding the last point, we have a list of candidate packages which will be discussed at the beginning.

### Secondary topic: package creation and submission

Documentation on creating, maintaining and submitting GAP packages is spread
over the reference manual, several pages of the GAP website and the example
package. The [current submission
process](https://www.gap-system.org/packages/authors/submit/) is not
transparent and leaves the requirements vague. We want to fix both.

**Documentation.** Consolidate and improve the documentation for package
authors. Relevant issues:
- [gap#5976](https://github.com/gap-system/gap/issues/5976): overhaul and unify the package author documentation
- [gap#5382](https://github.com/gap-system/gap/issues/5382): merge the package author pages of the GAP website into the reference manual
- [gap#5203](https://github.com/gap-system/gap/issues/5203): document how to deal with dependencies on other packages
- [PackageDistro#248](https://github.com/gap-system/PackageDistro/issues/248): document how to add a package to the distribution

**Submission process.** Overhaul it, as agreed at the last GAP Council meeting:
- Submissions go to [gap@gap-system.org](mailto:gap@gap-system.org) instead of
  support@gap-system.org. This is an open mailing list: anyone can join, and
  its archive is public. The documentation must say so clearly.
- The list will accept moderated posts from non-members, so submitters need not
  subscribe first.
- Possibly also accept submissions as GitHub issues or pull requests. These
  still need an accompanying email to gap@gap-system.org, so that everyone has
  a fair chance to see them.

**Requirements.** State upfront what a package must provide to be accepted, for
example:
- a non-trivial test suite that exercises the functionality of the package;
- a useful manual;
- tests that pass both with all packages loaded (`LoadAllPackages()`) and with
  only the needed packages loaded (no suggested packages), plus instructions
  for checking this locally.

Package authors, and anyone who has struggled to create or submit a package,
can help by pointing out where the current documentation or process failed
them, and by reviewing drafts.

### Secondary topic: preparing GAP 4.17.0

As is common during GAP Days, Max will work towards the next "major" GAP release.
If you'd like to help with that, you can find out how by talking to him at GAP Days.

<!-- 
## Things people are interested in working on:

- Max would like to release GAP 4.16.0
- Some people might work on their packages or even create new packages
- ...
- for more, see [our HackMD](https://hackmd.io/@gapdays/2026-fall)
-->
