# 2026 OpenSSF Mentorship Program - gittuf

Dates: June 1 - August 21

## Purpose

gittuf is a security layer for Git repositories, allowing for a security policy
to be applied independently of the service the repository may be hosted on (e.g.
GitHub, Gitlab, Bitbucket, etc…). The purpose of this project is to improve
gittuf in several domains, such as functionality, usability, and ease of access
for new users.

## Goal

**Improve gittuf's UI and UX**: gittuf is currently driven primarily by a
CLI-based workflow. The gittuf TUI is a work-in-progress UX improvement, where
users instead interact with gittuf more akin to a traditional desktop program.
The TUI is currently basic, and 

**Enable temporary/time-limited approvals**: There may be cases when a developer
may need to exercise some discretionary authority and approve something in
violation of the policy (e.g. a critical security patch at 4am may not be able
to be approved by the full team required in policy). Adding approvals that will
satisfy the policy for some duration of time (but not infinitely) would serve to
improve this aspect of gittuf.

## Desired Outcomes & Deliverables (1-2 mentees)

### Improve gittuf's UI and UX

This project should result in gittuf featuring a polished, first-class TUI, as
well as improvements to gittuf's UX in the CLI and API.

#### Deliverables

- Substantial improvements to the gittuf TUI, both functionally and
  aesthetically.
- Supporting documentation for how to use the updated TUI.
- Appropriate tests and internal improvements needed to support the upgraded
  TUI.

### Add functionality to gittuf to enable temporary/time-limited approvals

Some changes in a repository may need to violate the policy (e.g. a critical
security patch needing to be released at 4am, and only one developer is
available to approve changes at the time).

A variant of this feature is to allow for changes to be submitted to a
repository that must still be reviewed by someone else at a later time. These
changes should not be consumed until they are reviewed, but should not
necessarily pose a problem for the repository’s policy.

#### Deliverables

- A new feature that enables temporary/time-limited approvals in gittuf, as
  described above.
- Supporting documentation for how to use this new functionality in gittuf.
- Sufficient tests to ensure the proper operation of this new feature.

## Relevant Knowledge & Recommended Skills

### All projects

#### Skills

- Writing unit tests
- Documentation best practices

#### Technologies

- Git
- Go
- TUF

### UI and UX improvements

#### Skills

- GUI/TUI/UI/UX development skills 

#### Technologies

- Knowledge of the [Bubbletea TUI
  framework](https://github.com/charmbracelet/bubbletea), or similar framework.

## AI-based contributions

The mentorship program is intended to not only help mentees gain exposure to
working on production code, but also gain expereince with the workflow for
improving open source projects.

To that end, mentees may use AI in their contributions, so as long as:

- **All** code submitted to gittuf is manually reviewed by the mentee.
- Changes are well-documented and reviewable by a maintainer.
- The mentee fully understands the code they are submitting.
- Changes do not infringe on copyright/trademarks/etc...

Mentees that do not adhere to these requirements will be removed from the
program.

## Mentors

- Patrick Zielinski (patrick.z@nyu.edu)
- Aditya Sirish A Yelgundhalli (ayelgundhall@bloomberg.net)
