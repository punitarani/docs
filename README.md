# Peepal Docs

Peepal uses Mintlify to publish API documentation. The docs content lives in this folder and is driven by `docs.json`.

## Development

Install the Mintlify CLI and run a local preview from `apps/docs/`:

```bash
npm i -g mint
mint dev
```

Open `http://localhost:3000` to view the docs locally.

## Content structure

* `index.mdx`: API overview
* `quickstart.mdx`: First verification flow
* `concepts/`: Jobs, claims, reports, templates, webhooks
* `guides/`: Pagination, idempotency, errors
* `api-reference/`: OpenAPI-powered endpoints
