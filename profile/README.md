# Owlkei (OK)

Owlkei is a stack for building a complete web app with one set of tools: the interface, the
server and the parts between them.

Owlkei/UI is the interface: accessible components and page blocks that work in plain HTML or in
React. Owlkei/Go is the server: a web framework with storage, cache and WebSocket built in, which
ships an app as one binary. A Go route renders the same markup the components use, so the page
you design is the page you serve, with no glue layer to write.

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
