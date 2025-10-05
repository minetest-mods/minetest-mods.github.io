---
title: Welcome
layout: default
---


## Introduction

This project exists to **provide a semi-trusted source of Luanti/Minetest mods**.
The mod repositories are primarily developed by their author(s), or are taken care of
by the community, managed by the admins.

### General rules

* Keep the `master` branch stable as possible.
* Keep the mods in a usable and secure (maintained) state.
* Behave and respect each other.

## Roles

### 1. Organisation administrator

Brief: _Keeps an eye on all repositories, and manages them._

**Privileges:**

* Has full access to all minetest-mods repositories, which includes:
   * Repository creation and deletion
   * Access/permission management
   * Modifying content and managing user contributions (patches, issues, PRs)

**Duties:**

* Must respect the decisions of the mod author.
   * Must obtain a decision from the mod author (if active) before deciding on their own.
* Ensures that the mod requirements are met (section "How to add a mod?").
* Is in charge to resolve security-related topics.

### 2. Mod author

Brief: _Develops their mod, with or without external contributions._

**Privileges:**

* Has full access to their mod repository, which includes:
   * Access/permission management (e.g. co-authorship)
   * Modifying content and managing user contributions (patches, issues, PRs)
* If any action cannot be performed due to technical limitations - e.g. repository removal -
  the task shall be done by an admin.

**Duties:**

* Unless communicated explicitly, the mod author permits the community to maintain their
  project, managed by the co-authors or organisation admins.
* Ensures proper functionality of the mod.

### 3. Individual contributor

Brief: _Contributes to mods within the organisation._

**Privileges:**

* May propose commits, PRs, and submit issues.
* May have limited access to mod repositories - granted by mod authors or admins.

**Duties:**

* Must respect the decisions of the mod author.

## How to add a mod?

Mods added to this organisation must follow a few minimal requirements, which are listed below.

### Requirements

**Ownership**

* The original author of the mod should be the one submitting it to the minetest-mods
  organisation.
* Under circumstances (abandoned by author) we will consider
  forks.

**Licensing**

* An OSI-approved license is strongly preferred.
* Mods do not need to be Luanti-licensing compatible (meaning, GPL 3.0+ is accepted)
* Public Domain is not defined well in many countries, thus licenses such as
  MIT or CC0 should be used. Prefer CC0 over WTFPL.

**Mod structure**

* Required
   * A clear statement on the code and media licensing
   * A `mod.conf` file
* Strongly recommended
   * Screenshot
   * Matching LICENSE files

**Mod name**

Many mods have similar names but sometimes provide very different functionality.
For the purpose of clarity, conflicting names are to be prevented.
Repositories in the minetest-mods organisation should have clear and unambiguous
names.

### Submitting

In your request, please provide the following information:

* your mod name
* author (GitHub username, if available)
* the license(s) of your mod

By submitting a project, you acknowledge that you agree to the rules specified in this document.

* [Open Request (GitHub)](https://github.com/minetest-mods/minetest-mods.github.io/issues/new?title=New%20mod%20request) (preferred)
* [Open Request (Luanti Forums)](https://forum.luanti.org/viewtopic.php?t=13839) (alternative)

### Repository transfer

After opening a request ticket, you will be asked to initiate a "Transfer" request to move your mod.
If you want to fork your moved repository back, you are obviously free to do so.
You will be granted admin access on the moved repository. More information on the "Transfer" procedure
can be found here: [Transfer Information](https://help.github.com/articles/transferring-a-repository/)

We also send all mod owners a "become a member of minetest-mods" invitation.
This invitation does not need to be accepted, and is merely for you (and us)
to show who is participating in the minetest-mods organisation.
You do not require the invite. If you missed it, and would still like to become a listed member,
please request another invitation.

## Got any more questions?

Read the informal [forum announcement post](https://forum.luanti.org/viewtopic.php?t=13839),
and leave feedback or join the discussion.

Request a clarification of the rules stated above: [Open Request (GitHub)](https://github.com/minetest-mods/minetest-mods.github.io/issues/new).
