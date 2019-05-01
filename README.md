# CogniAPI OpenAPI Specification
[![Build Status](https://travis-ci.com/devis12/CogniAPI_spec.svg?branch=master)](https://travis-ci.com/devis12/CogniAPI_spec)

## Links

- [Reference Documentation (ReDoc)](https://devis12.github.io/CogniAPI_spec/)
- [SwaggerUI](https://devis12.github.io/CogniAPI_spec/swagger-ui/)
- OpenAPI Raw Files: [JSON](https://devis12.github.io/CogniAPI_spec/openapi.json) [YAML](https://devis12.github.io/CogniAPI_spec/openapi.yaml)

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `npm install` in the repo root

### Usage

#### `npm start`
Starts the development server.

#### `npm run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`
Validates the spec.

#### `npm run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.
