---
title: Manifest of the Minetest-Mods team and Mod content
layout: default
---

This document describes the organization and requirements of the Minetest-Mods team, it's goal
and regulations.

## Goal of this project

This project exists to provide a method for Luanti players and server operators
to have a semi-trusted source of Luanti/Minetest Mods.

Minetest mods are distributed separately and there is not a single source of mods.
This has lead to hundreds of Luanti Mods around in equal amount of locations on
the internet, and this is bad for players, server operators and developers alike.

By providing a single hosting namespace for Luanti mods, this project serves as a
method of telling users that a specific version of a Minetest mod is the preferred
or recommended version of that mod. This helps to alleviate the issues of having many
forks of Minetest mods around.

Authors who host their mods in the minetest-mods project explicitly
allow the minetest-mods admins to merge changes into their mods. This allows the authors
of these mods to "sign out" for a while knowing that their mods are being taken care of,
and provides a method for users to continue using the exact same mods long after the
original author has moved on since these mods will still be maintained.

## Contents of the project

This project hosts any Luanti mod that mod authors have contributed to the minetest-mods
project, permitted these mods are properly licensed as an Open Source project, and do
not present any other legal issues.

* OSI approved license are strongly preferred.
* Mods do not need to be minetest-licensing compatible (meaning, (A)GPL3.0+ is fine).
* Non-OSI licenses may be acceptable, but this is determined on a one-by-one case.
* Pure Public Domain is not acceptable, however WTFPL, MIT or similar usually is acceptable.

The project admins reserve the right to discontinue, remove or refuse any project based
on legality, content or other, at their discretion.

⚠ **New mods are not being accepted into the project at this time** ⚠

The original author of the mod should be the one submitting it to the minetest-mods
project. Only in exigent circumstances will a mod fork be allowed, and admins reserve
the right to refuse mod forks at their discretion. In general, forks are only allowed
if the original author clearly no longer maintains the project, and if the project has
been properly licensed by the original author, and last, that the project license has
remained unchanged in the fork.

Modpacks (groups of mods bundled together) are not permitted in minetest-mods, as they
make management more difficult and prevent users from installing only parts of of a
modpack. For cooperative maintenance of modpacks, see the minetest-modpacks team instead,
or look at the minetest-games project. (At the time of writing of this document, those
two teams/projects do not exist).

Mods should ensure that they have all the needed files present to assure dependencies
and mod metadata is present. description.txt is required to be present, and we strongly
urge mods to have mod.conf present, as well as a screenshot.png file, a LICENSE file
and a README.md file as well.

## Member organization

The project's team members are organized into specific roles:

### 1. project administrator (admin)

Project administrators have full access to all minetest-mods projects, and can create
new ones, merge PR's in any project, push code to any project, remove any project from
the minetest-mods project, maintain memberships and permissions.

* admin shall verify mod eligibility and add mod if they meet requirements.
* admin shall not push code directly to any mod where they are not also the author.
* admin shall allow author to maintain their contributed mod as they see fit. Moreover,
admin shall not merge PRs in mods until a reasonable time has elapsed, and author has
been given a reasonable time to review or object to a PR.

### 2. project author (author)

* author grants admin permission to review, reject or accept outstanding PR's that have gone
unreasonably long without merging.
* author grants admin permission to remove his mod from the project.
* author may grant permission to individual committers to co-maintain his project, including
merging PR's.
* author may manage committers as he sees fit.
* author reasonably works with admin to assure his mod works together with other mods in the
project, such that it can coexist and interoperate properly with them, avoid breaking other
mods.

### 3. individual contributor (committer)

* committer may manage PR's, push code to mod that they have been granted access to.
* committer shall due their due dilligence cooperating with other committer, author and
admin in maintaining the mod as a team.

## Namespace Organization

Many different versions of mods exists, and many mods have similar names but sometimes
provide very different functionality. For the purpose of clarity, comflicting names are
to be prevented, and mods in the minetest-mods project should have clear and unambiguous
names.

Namespace organization may require admin and author to cooperate to establish proper
API's and propagate their use through other mods. Authors reasonably should join this
discussion and cooperate, to avoid mod conflicts and improve mod harmony.

## A note on legacy

Mod author and admin should do their best to avoid supporting a legacy of old world
data, as this generally does not provide the best atmosphere to develop new mods and
mod features going forward. At times it may be best to remove support for old Luanti
versions, old APIs or game object types. We encourage people to provide fallback
code for old code, but would prefer if people code with a healthy attitude of cleaning
out old code instead.

As such, we recommend that people actively remove code that exists solely for the
purpose of old world data, old game versions or old supporting mods. For the purpose
of this document, "old" means "more than 1 year old, or 365 days". While admins do not
want to police or enforce this rule, they retain the privilege to remove code that
violates this rule at their discretion.
