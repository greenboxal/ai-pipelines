# ai-pipelines

[![license](https://img.shields.io/badge/license-MIT-blue)](https://github.com/greenboxal/ai-pipelines/blob/master/LICENSE)
[![Go Reference](https://pkg.go.dev/badge/github.com/greenboxal/ai-pipelines.svg)](https://pkg.go.dev/github.com/greenboxal/ai-pipelines)

Infrastructure for building AI pipelines.

Note: This project is still in early development and is not ready for production use.
Note: This repository is a migration/rewrite/refactor of the [original code](https://github.com/greenboxal/aip), which is WIP.

## Features

* Document-based database ORM
  * Strongly typed
  * Support for multiple backends
  * Support for secondary indexes such as vector/embedding indexes
  * Support for namespacing, allowing isolated enclaves of data
* GraphQL API
  * Support for real-time subscriptions and pubsub
* Universal AST Graph service
  * Aids context retrieval by following both semantic and lexical references
  * Support for natural language through Markdown-like semantics
  * Support for code languages through pluggable parsers
  * Allows in-place modification of the AST
* Tracing
  * Not to be confused with distributed tracing, like OpenTelemetry
  * Allows tracing of data flow through the pipeline
  * Inspect, replay or _fork_ chain-of-thoughts
    * Allows quick iteration and experimenting
    * Shows documents that were accessed during context retrieval
    * Show any documents created or modified after the execution of the chain
    * Git-like semantics for branching, merging and diffing
* Wiki-like content management system
  * Markdown
  * Render any document defined in the database
  * Custom views associated with each document type.
  * Frontend using React, MaterialUI and React-Admin.

Check each subproject readme for more details.

## License
MIT. See [LICENSE](LICENSE) for more details.
