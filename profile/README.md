<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./owlkei-horizontal-dark.svg">
    <img src="./owlkei-horizontal-light.svg" alt="Owlkei" width="320">
  </picture>
</p>

<p align="center"><strong>Owlkei (OK)</strong></p>

<p align="center">
  <a href="https://owlkei.com">owlkei.com</a> ·
  <a href="https://x.com/owlkeidev">X @owlkeidev</a> ·
  <a href="https://bsky.app/profile/owlkei.bsky.social">Bluesky @owlkei.bsky.social</a>
</p>

Owlkei is a UI component library and a Go web framework that are built to fit together. An Owlkei/Go
page route renders Owlkei/UI's HTML markup, and the same components work in React. Storage,
cache and WebSocket come with the framework, and an app ships as one binary.

## Repositories

- **[Owlkei/SDK](https://github.com/owlkei/sdk)**: the client for Owlkei/Go apps, in TypeScript and Go.
  It speaks WebSocket today; HTTP comes next.
- **Owlkei/UI** (not public yet): components, blocks and templates in plain HTML and React, with
  nine design styles, light and dark modes and WCAG AA contrast.
- **Owlkei/Go** (not public yet): routes come from method names (`READ_users_BY_id` answers
  `GET /users/{id}`), and dependency injection wires modules, controllers and services.
- **Owlkei/CLI** (planned): `owlkei new` scaffolds a project, and `owlkei routes` prints an app's
  route table, with JSON output for editors and CI.

Nothing is released yet. Releases and docs will be at [owlkei.com](https://owlkei.com).
