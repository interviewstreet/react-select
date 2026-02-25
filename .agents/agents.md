# react-select - Agent Guide

This is the agent-facing guide for working in this repository.

## Project Context
- The Select Component for React.js

## Setup
See [`agents.yaml`](./agents.yaml) for prerequisites, commands, and ports.

### Setup Hints
- `nvm` may not be loaded in your shell. If `nvm: command not found`, source it first.
- `yarn start` runs in the foreground — background it the same way.

## Running the App
- Clone the repo
- Install: `yarn install`
- Dev: `yarn start &`
- Access: `http://localhost:3000`

## Architecture
- React select component library (monorepo)
- Uses preconstruct for building
- Entry point: `packages/react-select/src/index.js`

## Working Agreement
- Write modular code
- Keep testable
- Incremental validation
- Commit meaningful checkpoints
- Write tests
- Validate before handoff
