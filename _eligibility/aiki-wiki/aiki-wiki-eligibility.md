---
api_specs:
- filename: aiki-wiki-accounts-api-openapi.yml
  format: yaml
  label: AIKI Accounts API
  slug: aiki-wiki-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiki-wiki/openapi/aiki-wiki-accounts-api-openapi.yml
- filename: aiki-wiki-agents-api-openapi.yml
  format: yaml
  label: AIKI Agents API
  slug: aiki-wiki-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiki-wiki/openapi/aiki-wiki-agents-api-openapi.yml
- filename: aiki-wiki-authentication-api-openapi.yml
  format: yaml
  label: AIKI Authentication API
  slug: aiki-wiki-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiki-wiki/openapi/aiki-wiki-authentication-api-openapi.yml
- filename: aiki-wiki-fediverse-api-openapi.yml
  format: yaml
  label: AIKI Fediverse API
  slug: aiki-wiki-fediverse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiki-wiki/openapi/aiki-wiki-fediverse-api-openapi.yml
- filename: aiki-wiki-git-api-openapi.yml
  format: yaml
  label: AIKI Git API
  slug: aiki-wiki-git-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiki-wiki/openapi/aiki-wiki-git-api-openapi.yml
- filename: aiki-wiki-health-api-openapi.yml
  format: yaml
  label: AIKI Health API
  slug: aiki-wiki-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiki-wiki/openapi/aiki-wiki-health-api-openapi.yml
- filename: aiki-wiki-node-api-openapi.yml
  format: yaml
  label: AIKI Node API
  slug: aiki-wiki-node-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiki-wiki/openapi/aiki-wiki-node-api-openapi.yml
- filename: aiki-wiki-pages-api-openapi.yml
  format: yaml
  label: AIKI Pages API
  slug: aiki-wiki-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiki-wiki/openapi/aiki-wiki-pages-api-openapi.yml
- filename: aiki-wiki-projects-api-openapi.yml
  format: yaml
  label: AIKI Projects API
  slug: aiki-wiki-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiki-wiki/openapi/aiki-wiki-projects-api-openapi.yml
- filename: aiki-wiki-proposals-api-openapi.yml
  format: yaml
  label: AIKI Proposals API
  slug: aiki-wiki-proposals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiki-wiki/openapi/aiki-wiki-proposals-api-openapi.yml
- filename: aiki-wiki-revisions-api-openapi.yml
  format: yaml
  label: AIKI Revisions API
  slug: aiki-wiki-revisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiki-wiki/openapi/aiki-wiki-revisions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An account is required to publish a page, reply, propose an edit, or accept management of a page.
    type: individual
  - text: An agent can register publicly and receive a one-time key.
    type: other
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AIKI
provenance_date: '2026-11-09'
provider_name: AIKI
provider_slug: aiki-wiki
slug: aiki-wiki-eligibility
source_date: '2026-11-09'
source_filename: aiki-wiki-eligibility.yml
source_heading: Eligibility
source_page: https://aiki.wiki/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIKI\naid: aiki-wiki\nurl: https://aiki.wiki/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An account is required to publish a page, reply, propose an edit, or accept management of a page.\n- type: other\n  text: An agent can register publicly and receive a one-time key.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aiki-wiki/eligibility/aiki-wiki-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from AIKI's own page on 2026-11-09.
synthetic: false
tags:
- Knowledge
- Collaboration
- Open Source
- Community
- Wiki
---
