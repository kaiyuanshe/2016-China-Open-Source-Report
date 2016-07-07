##TODO
需要翻译

## Introduction

Dear workgroup member. Thank you for investing the time and energy to help
make this project as useful as possible. Maintaining a project is difficult,
sometimes unrewarding work.  Sure, you will get to contribute cool
features to the project. But most of your time will be spent reviewing,
cleaning up, documenting, answering questions, justifying design
decisions - while everyone has all the fun! But remember - the quality
of the workgroup members work is what distinguishes the good projects from the
great.  So please be proud of your work, even the unglamourous parts,
and encourage a culture of appreciation and respect for *every* aspect
of improving the project - not just the hot new features.

This document is a manual for workgroup members old and new. It explains what
is expected of workgroup members, how they should work, and what tools are
available to them.

This is a living document - if you see something out of date or missing,
speak up!

## What are a workgroup member's responsibility?

It is every workgroup member's responsibility to:

* 1) Expose a clear roadmap for improving their component.
* 2) Deliver prompt feedback and decisions on pull requests.
* 3) Be available to anyone with questions, bug reports, criticism etc.
  on their component. This includes IRC and GitHub issues and pull requests.
* 4) Make sure their component respects the philosophy, design and
  roadmap of the project.

## How are decisions made?

Short answer: with pull requests to the project repository.

This project is an open-source project with an open design philosophy. This
means that the repository is the source of truth for EVERY aspect of the
project, including its philosophy, design, roadmap and APIs. *If it's
part of the project, it's in the repo. It's in the repo, it's part of
the project.*

As a result, all decisions can be expressed as changes to the
repository. An implementation change is a change to the source code. An
API change is a change to the API specification. A philosophy change is
a change to the philosophy manifesto. And so on.

All decisions affecting this project, big and small, follow the same 3 steps:

* Step 1: Open a pull request. Anyone can do this.

* Step 2: Discuss the pull request. Anyone can do this.

* Step 3: Accept (`LGTM`) or refuse a pull request. The relevant workgroup members do
this (see below "Who decides what?")

### I'm a workgroup member, should I make pull requests too?

Yes. Nobody should ever push to master directly. All changes should be
made through a pull request.

## Who decides what?

All decisions are pull requests, and the relevant workgroup members make
decisions by accepting or refusing the pull request. Review and acceptance
by anyone is denoted by adding a comment in the pull request: `LGTM`.
However, only currently listed `MAINTAINERS` are counted towards the required
two LGTMs. In addition, if a workgroup member has created a pull request, they cannot
count toward the two LGTM rule (to ensure equal amounts of review for every pull
request, no matter who wrote it).

Overall the workgroup member system works because of mutual respect across the
workgroup members of the project.  The workgroup members trust one another to make decisions
in the best interests of the project.  Sometimes workgroup members can disagree and
this is part of a healthy project to represent the point of views of various people.

Even though the workgroup member system is built on trust, if there is a conflict
with the chief workgroup member on a decision, their decision can be challenged
and brought to the technical oversight board if two-thirds of the
workgroup members vote for an appeal. It is expected that this would be a
very exceptional event.


### How are workgroup members added?

The best workgroup members have a vested interest in the project.  Workgroup members
are first and foremost contributors that have shown they are committed to
the long term success of the project.  Contributors wanting to become
workgroup members are expected to be deeply involved in contributing code,
pull request review, and triage of issues in the project for more than two months.

Just contributing does not make you a workgroup member, it is about building trust
with the current workgroup members of the project and being a person that they can
depend on and trust to make decisions in the best interest of the project.  The
final vote to add a new workgroup member should be approved by over 66% of the current
workgroup members with the chief workgroup member having veto power.  In case of a veto,
conflict resolution rules expressed above apply.  The voting period is
five business days on the Pull Request to add the new workgroup member.


### What is expected of workgroup members?

Part of a healthy project is to have active workgroup members to support the community
in contributions and perform tasks to keep the project running.  Workgroup members are
expected to be able to respond in a timely manner if their help is required on specific
issues where they are pinged.  Being a workgroup member is a time consuming commitment and should
not be taken lightly.

When a workgroup member is unable to perform the required duties they can be removed with
a vote by 66% of the current workgroup members with the chief workgroup member having veto power.
The voting period is ten business days.  Issues related to a workgroup member's performance should
be discussed with them among the other workgroup members so that they are not surprised by
a pull request removing them.

## Thanks
https://github.com/opencontainers/project-template/blob/master/MAINTAINERS_GUIDE.md
