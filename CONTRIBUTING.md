# Table of Contents

- [Contribution Guidelines](#contribution-guidelines)
  - [Introduction](#introduction)
  - [Setup & Vault Consistency](#setup-and-vault-consistency)
  - [Bug reports](#bug-reports)
  - [Discuss your design](#discuss-your-design)
  - [Verification Process](#verification-process)
  - [Formatting Standard](#formatting-standard)
  - [Release Cycle](#release-cycle)
  - [Ownership](#ownership)

# Introduction

This document explains how to contribute changes to Freedomcraft Wiki Vault.

> Sensitive security-related issues should be reported to
[security@freedomcraft.email](mailto:security@freedomcraft.email).

For setting up a Personal Vault see [Obsidian.md Community Hub](https://publish.obsidian.md/hub)

# Setup and Vault Consistency

To contribute, please [download the latest version](https://github.com/FreedomCraft-Network/wiki/releases/latest) of this vault and open it in Obsidian. This is important to avoid duplicating content, and allows you to use the autocomplete when linking to other notes, searching and following our content guidelines.

Because Personal Knowledge Management is usually (as it name states) _highly_ personal, we have added a few rules about how we use Obsidian features to keep this Community vault consistent (and to preserve our sanity 🙂)

- **Tags**: We mostly use tags to indicate the status of a Task. You can find more details in the [[Knowledgebase/References/📍 Tag Glossary|📍 Tag Glossary]].
- **Files & Links**: Make sure that any time you add or edit a note, your settings are configured correctly. This should be set up by default. To sum up:
    - Configure `Location of new notes` to go the [[Inbox/🗂️ New Notes - Overview|🗂️ Inbox]] folder.
    - Links should be set to `Relative Paths` and wiki links must be enabled.
    - The `Default location for new attachments` should be the folder [./assets/]
    - Example: [![image](https://cdn.freedomcraft.systems/osidian/examples/file-settings.PNG)]

- **Folders**: We have roughly pre-defined the structure of the vault. _Before adding new folders, please open an issue to discuss the changes you'd like to propose._

Now that you have configured Obsidian, you are ready to do your first contribution! Have a look at the [[Knowledgebase/Guidelines/Contributing Guidelines/Types of Contributions|Types of Contributions]], and depending on what you want to contribute open the linked note for further instructions.  

Once you have added or edited the note using Obsidian, come back and check out [[Knowledgebase/Guidelines/Contributing Guidelines/Submitting your Contribution|Submitting your Contribution]].

# Bug reports

Please search the issues on the issue tracker with a variety of keywords
to ensure your bug is not already reported.

If unique, [open an issue](https://github.com/FreedomCraft-Network/wiki/issues/new).

Please write clear, concise instructions so we can reproduce the behavior—
even if it seems obvious. The more detailed and specific you are,
the faster we can fix the issue. 

Please be kind, remember that your fellow FreedomCraft Staff work as volunteers.

# Discuss your design

The project welcomes submissions. If you want to change or add something,
please let everyone know what you're working on—[file an issue](https://github.com/FreedomCraft-Network/wiki/issues/new)!
Significant changes must go through the change proposal process
before they can be accepted. To create a proposal, file an issue with
your proposed changes documented, and make sure to add the label "proposal".

This process gives everyone a chance to validate the design, helps
prevent duplication of effort, and ensures that the idea fits inside
the goals for the project and tools. It also checks that the design is
sound before code is written; the code review tool is not the place for
high-level discussions.


# Verification Process

Changes to FreedomCraft Wiki Vault must be reviewed before they are accepted—unless they are an owner or a maintainer. We use GitHub's
pull request & review workflow to do that. GitHub ensures every PR is reviewed by at least 1 maintainer.

Please try to make your pull request easy to review for us.

* Make small pull requests. The smaller, the faster to review and the
  more likely it will be merged soon.
* Don't make changes unrelated to your PR. Maybe there are typos on
  some comments, maybe refactoring would be welcome on a function... but
  if that is not related to your PR, please make *another* PR for that.
* Split big pull requests into multiple small ones. An incremental change
  will be faster to review than a huge PR.

# Release Cycle

Before we reach v1 there is no fixed release cycle.

# Ownership

This repo is part of the FreedomCraft Project and as such, all contributions are part of that project's
governance.