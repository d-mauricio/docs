# Jurat Developer Docs

Mintlify documentation for the Jurat Recovery API and SDK.

## Local Preview

Install the Mintlify CLI globally:

```bash
npm i -g mint
```

Then run from this repository root:

```bash
mint dev
```

Alternatively:

```bash
npx mint dev
```

## OpenAPI

The API reference is generated from:

```txt
api-reference/openapi.yaml
```

Validate it with:

```bash
mint openapi-check api-reference/openapi.yaml
```

## Deployment

Mintlify deploys this repository through the GitHub app. Push changes to the connected branch to publish.
