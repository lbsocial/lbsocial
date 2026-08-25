# Repository Agent Instructions

## Scope and ownership

This repository owns the public `github.com/lbsocial` profile and Course/resource catalog.

- Codex maintains profile and catalog content only under an active, owner-authorized Issue.
- Antigravity does not maintain this profile repository. It owns separately authorized Course repositories, Course sites, lessons, code, notebooks, HTML/JavaScript, diagrams, animations, and the Course-site contract.
- Local AI does not write to GitHub repositories, Issues, pull requests, Pages, or account settings.
- This repository may link to a Course after it is public, but it does not define or implement the Course-site contract.

## Roadmap and pull requests

- Roadmap and implementation Issues remain in `lbsocial/lbsocial-local-ai`.
- Cross-repository pull requests must reference the controlling Issue with the full form `Refs lbsocial/lbsocial-local-ai#<issue>`.
- Agents must use an issue-specific branch, keep changes within the active Issue, and complete required validation and review before owner handoff.
- Agents must not merge their own pull requests or close the controlling roadmap Issue.

## Account-level boundary

Profile pins, organization or account settings, repository settings, and other GitHub account-level mutations require separate, explicit owner authorization. Repository-file work does not authorize those changes.
