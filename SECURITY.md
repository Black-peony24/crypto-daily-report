# Security Policy

## Reporting a Vulnerability

Please do not open a public issue for security problems.

Use GitHub's private vulnerability reporting on this repository
(Security tab → Report a vulnerability), or email the maintainer
listed on the GitHub profile.

Expect an initial response within 7 days.

## Scope

This project runs a headless browser, makes outbound HTTP requests to
third-party APIs, renders remote text into an HTML template, reads API
keys from environment variables, and writes files to disk. Reports
concerning any of the following are in scope:

- Template or HTML injection via upstream API content
- Command or argument injection through CLI parameters
- Path traversal in output file handling
- Credential exposure through logs, tracebacks, or rendered output
- Dependency or supply-chain issues in the pinned requirements

## Supported Versions

The latest release on `main` is supported.
