# BarelyReal Deskflow Fork Roadmap

This document tracks fork-specific work that connects Deskflow-style desktop sharing with BarelyReal's macOS and Windows workflow.

## Goals

- Keep this fork close enough to upstream Deskflow that useful improvements can be proposed back as focused pull requests.
- Explore reliability and usability improvements for keyboard, mouse, and clipboard sharing.
- Document security-sensitive areas before changing behavior around input, networking, or clipboard data.

## Near-Term Work

- Track the upstream server address history PR and adjust it based on maintainer feedback.
- Review client setup friction on macOS and Windows.
- Identify small issues where BarelyReal and Deskflow have overlapping needs.
- Keep fork changes clearly separated from upstream-ready patches.

## Security Notes

BarelyReal and Deskflow-style applications touch sensitive local surfaces:

- keyboard and mouse input;
- clipboard data;
- local network discovery and connections;
- operating-system permissions;
- release signing and packaging.

Changes in these areas should be reviewed carefully and kept small enough to test.

## Upstream Policy

When an improvement is generally useful to Deskflow users, it should be opened as a clean upstream pull request. Fork-only experiments should remain documented here until they are mature enough to split into reviewable patches.
