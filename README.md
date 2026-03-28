# Offload docs

This repository contains the Mintlify documentation site for Offload / CasesAI.

## What is documented

The site currently covers:

- product overview and quickstart
- case concepts and lifecycle
- result schema guidance
- human-in-the-loop workflows
- API reference for `/cases`
- outbound webhook payloads

## Local development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

From this directory, start a local preview:

```bash
mint dev
```

The preview is usually available at `http://localhost:3000`.

## Validation

Check for broken links before publishing:

```bash
mint broken-links
```

## Publishing

This repo is intended to be deployed through Mintlify. Push changes through your normal Git workflow and use the Mintlify GitHub integration or deployment flow configured for your team.
