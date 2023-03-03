# Nix documentation team

The Nix documentation team was formed to flatten the infamous learning curve.

## Goals

- ease learning, increase onboarding success and user retention
- improve organization of knowledge
- lead, guide, and support related community efforts

## Motivation

To improve the state of affairs with Nix onboarding and documentation, we have to tackle some big issues and work through many small ones:
implement structural changes after gathering the necessary social support;
fix numerous little problems and help people get their contributions merged.

It requires significant time or resources to do this consistently.
The team is built around that limitation, and therefore organized as a praxicracy:
you are in charge if and only if you get the work done.

The team’s reason to exist is to make that principle discoverable and reproducible by laying groundwork and setting examples.

## Members

- Valentin Gagarin ([@fricklerhandwerk])

  Nix documentarian, [Tweag]

- Silvan Mosberger ([@infinisil])

  Nixpkgs maintainer, [Tweag]

[@fricklerhandwerk]: https://github.com/fricklerhandwerk
[@infinisil]: https://github.com/infinisil

[Tweag]: https://tweag.io

## Responsibilities

### Team

Ordered by priority:

1. Establish and maintain guidelines for contributing to documentation in the Nix ecosystem
1. Extend and curate [nix.dev] as the central learning resource
1. Review and merge [Nix pull requests], [Nixpkgs pull requests], and [NixOS pull requests] concerning documentation
1. Keep track of [Nix issues], [Nixpkgs issues], and [NixOS issues] concerning documentation
1. Maintain and develop documentation infrastructure
1. Monitor the [*Documentation* Discourse category]
1. Monitor the [*Nix\* Documentation* Matrix room]

[nix.dev]: https://nix.dev
[Nix pull requests]: https://github.com/NixOS/nix/pulls?q=is%3Aopen+is%3Apr+label%3Adocumentation
[Nixpkgs pull requests]: https://github.com/NixOS/nixpkgs/pulls?q=is%3Aopen+is%3Apr+label%3A%228.has%3A+documentation%22%2C%226.topic%3A+documentation%22
[NixOS pull requests]: https://github.com/NixOS/nixpkgs/pulls?q=is%3Aopen+is%3Apr+label%3A%226.topic%3A+nixos%22+label%3A%228.has%3A+documentation%22%2C%226.topic%3A+documentation%22
[Nix issues]: https://github.com/NixOS/nix/issues?q=is%3Aopen+is%3Aissue+label%3Adocumentation
[Nixpkgs issues]: https://github.com/NixOS/nixpkgs/issues?q=is%3Aopen+is%3Aissue+label%3A%229.needs%3A+documentation%22
[NixOS issues]: https://github.com/NixOS/nixpkgs/issues?q=is%3Aopen+is%3Aissue+label%3A%229.needs%3A+documentation%22+label%3A%226.topic%3A+nixos%22
[*Documentation* Discourse category]: https://discourse.nixos.org/c/dev/documentation/25
[*Nix\* Documentation* Matrix room]: https://app.element.io/#/room/#docs:nixos.org
[changes to the NixOS Wiki]: https://matrix.to/#/#nixos-wiki:utzutzutz.net

In addition, the team has to perform administrative tasks which it distributes across team members:

- Triage issues and pull requests
- Curate the [GitHub project board]
- Invite new participants
- Schedule meetings
- Moderate and keep to the schedule
- Take and publish meeting notes
- Keep team information up to date

Team members are expected to become maintainers and take ownership of some piece of documentation they care about.
The team lead supports team members who want to take on [maintainer responsibilities](./responsibilities.md).

### Team lead

- Set a direction and agendas
- Represent the team
- Publish announcements and reports
- Exercise elevated privileges:
  - Manage permissions for the [GitHub team] and the [GitHub project board]
  - Update [NixOS Calendar] events
  - Merge pull requests approved by team members

[GitHub team]: https://github.com/orgs/NixOS/teams/documentation-team
[GitHub project board]: https://github.com/orgs/NixOS/projects/15 

## Team meetings

The team holds weekly meetings on Thursdays 17:30-18:30 (Europe/Berlin):
- [NixOS calendar](https://calendar.google.com/calendar/u/0/embed?src=b9o52fobqjak8oq8lfkhg3t0qg@group.calendar.google.com)
- [Discourse community calendar](https://discourse.nixos.org/t/community-calendar/18589)

### Meeting links

- [Jitsi conference](https://meet.jit.si/nix-documentation)
- [Meeting notes scratchad][collaborative scratchad]
- [GitHub project board]

[Meeting notes](https://discourse.nixos.org/search?q=documentation%20team%20meeting%20%23dev%3Adocumentation%20order%3Alatest)

### Meeting protocol

The purpose of the meetings is to
- make strategic decisions
- coordinate efforts
- exchange experience and insights.

As the Nix community is distributed globally, available time for synchronous communication is highly limited and therefore very valuable.
Writing is still the primary medium of communication.

To keep discussions highly focused and make their results accessible, we will:

- prepare meeting agendas as pull requests on the [nix.dev repository](https://github.com/NixOS/nix.dev)
  - estimate and follow estimated discussion time for each agenda item
  - pull requests have priority
  - invite authors to the meetings if possible
- prepare notes in a [collaborative scratchpad]
- add notes to existing issues or pull requests as a comment
- merge pull requests made on the last session
- submit new pull requests or issues
- post the meeting protocol on the [*Documentation* Discourse category]
- update calendar invitations

[collaborative scratchpad]: https://pad.lassul.us/p-Y8MjU2SdSD5qO1fnpCPA?edit#

Meeting notes should contain:

- date of meeting
- list of attendees
- results and links to GitHub issues and pull requests for each agenda item

## Contributing

If you want to help immediately, please see [How to contribute to documentation](./how-to-contribute-to-documentation.md).

## Sponsoring

[@fricklerhandwerk] serves as a provisional team lead since 2023-02, sponsored by [Antithesis](https://antithesis.com).
[@infinisil] works on the team since 2022-11, sponsored by [Tweag].

[@lucperkins](https://github.com/lucperkins) served as the team lead from 2022-11 to 2023-01, sponsored by [Determinate Systems](https://determinate.systems).

[@fricklerhandwerk] served as the team lead from 2022-05 to 2022-10, sponsored by [Tweag]

