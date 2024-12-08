# Turbo Repo Remix Template

A template for a monorepo using [pnpm](https://pnpm.io/) and [Turborepo](https://turbo.build/repo/docs) to support [Remix](https://remix.run) apps.

## Prerequisites

To get started install [Node version 20+](https://nodejs.org/en/download/package-manager), and [pnpm](https://pnpm.io/) (globally).

## Dependency Management

We use pnpm, for [reasons mentioned here](https://pnpm.io/pnpm-vs-npm). Install all dependencies by running `pnpm i` in the root. 

## Project Structure

The template is configured as a pnpm workspace.
There are two subfolders for code: 

- `apps` which contains all the apps.
- `packages` which contains all shared code and configuration.

## Code Style

Code style is determined by [Biome](https://biomejs.dev/). There are three code style commands included:

- `check`: lints, formats, and fixes imports. Automatically run on commit.
- `format`: formats the code
- `lint`: lints code

## Testing

The following testing tools are included in dev dependencies:

- [Cypress](https://www.cypress.io/) for E2E testing.
- [Vitest](https://vitest.dev/) for unit testing.

## Building

For building and bundling, the following tools are included:

- [TSup](https://github.com/egoist/tsup) for building and bundling Typescript libraries.
- [Typescript](https://www.typescriptlang.org/) main development language.
- [Vite](https://vite.dev/) for building web applications.

## Miscellaneous

The following are additional support tools:

- [Dotenv](https://www.dotenv.org/) for managing environment variables. Includes dotenv-vault for storing environment variables securely only.
- [TSX](https://tsx.is/) for executing Typescript script files.