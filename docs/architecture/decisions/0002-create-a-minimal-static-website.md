# 2. Create a minimal static website

Date: 2023-11-03

## Status

Accepted

## Context

I need a single page to introduce myself and provide links to other websites I'm on.
The content will not change often.

## Decision

Use static HTML, CSS, and assets, without JavaScript or build tooling.

## Consequences

The website will be deployable with no build step.

The website will load quickly.

The lack of JS means content will not be dynamic.

The lack of build tooling means no access to code generation that could ease some tasks.
