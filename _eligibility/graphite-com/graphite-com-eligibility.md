---
api_specs:
- filename: graphite-com-authentication-api-openapi.yml
  format: yaml
  label: Graphite Authentication API
  slug: graphite-com-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/graphite-com/openapi/graphite-com-authentication-api-openapi.yml
- filename: graphite-com-github-app-api-openapi.yml
  format: yaml
  label: Graphite GitHub App API
  slug: graphite-com-github-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/graphite-com/openapi/graphite-com-github-app-api-openapi.yml
- filename: graphite-com-merge-queue-api-openapi.yml
  format: yaml
  label: Graphite Merge Queue API
  slug: graphite-com-merge-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/graphite-com/openapi/graphite-com-merge-queue-api-openapi.yml
- filename: graphite-com-stacks-api-openapi.yml
  format: yaml
  label: Graphite Stacks API
  slug: graphite-com-stacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/graphite-com/openapi/graphite-com-stacks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing or using the Services on behalf of a company or other entity, (a) you represent and warrant that (i) you are an authorized representative of the entity with authority to bind the entity to the Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated decision-making without human review
    text: use the AI Features for automated decision-making that has legal or similarly significant effects on individuals, unless it does so with adequate human review and in compliance with applicable laws
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
name: Graphite
provenance_date: '2026-11-09'
provider_name: Graphite
provider_slug: graphite-com
slug: graphite-com-eligibility
source_date: '2026-11-09'
source_filename: graphite-com-eligibility.yml
source_heading: Eligibility
source_page: https://graphite.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Graphite\naid: graphite-com\nurl: https://graphite.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing or using the Services on behalf of a company or other entity, (a) you represent and\n    warrant that (i) you are an authorized representative of the entity with authority to bind the entity to the\n    Terms\nrestricted_uses:\n- summary: Automated decision-making without human review\n  text: use the AI Features for automated decision-making that has legal or similarly significant\
  \ effects on individuals,\n    unless it does so with adequate human review and in compliance with applicable laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/graphite-com/eligibility/graphite-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Graphite's own page on 2026-11-09.
synthetic: false
tags:
- Code Review
- Stacked PRs
- merge-queue
- AI Code Review
- Developer Tools
- GitHub
---
