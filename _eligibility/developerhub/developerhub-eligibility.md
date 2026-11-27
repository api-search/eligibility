---
api_specs:
- filename: developerhub-documentation-api-openapi.yml
  format: yaml
  label: DeveloperHub Documentation API
  slug: developerhub-documentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/developerhub/openapi/developerhub-documentation-api-openapi.yml
- filename: developerhub-project-api-openapi.yml
  format: yaml
  label: DeveloperHub Project API
  slug: developerhub-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/developerhub/openapi/developerhub-project-api-openapi.yml
- filename: developerhub-reader-access-api-openapi.yml
  format: yaml
  label: DeveloperHub Reader Access API
  slug: developerhub-reader-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/developerhub/openapi/developerhub-reader-access-api-openapi.yml
- filename: developerhub-changelog-api-openapi.yml
  format: yaml
  label: DeveloperHub Changelog API
  slug: developerhub-changelog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/developerhub/openapi/developerhub-changelog-api-openapi.yml
- filename: developerhub-page-api-openapi.yml
  format: yaml
  label: DeveloperHub Page API
  slug: developerhub-page-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/developerhub/openapi/developerhub-page-api-openapi.yml
- filename: developerhub-reference-api-openapi.yml
  format: yaml
  label: DeveloperHub Reference API
  slug: developerhub-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/developerhub/openapi/developerhub-reference-api-openapi.yml
- filename: developerhub-version-api-openapi.yml
  format: yaml
  label: DeveloperHub Version API
  slug: developerhub-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/developerhub/openapi/developerhub-version-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this agreement on behalf of a company or other legal entity, the terms “you” and “your” shall refer to the entity.
    type: business
  minimum_age:
    text: You must be 13 years or older to use DeveloperHub.
    value: '13'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: You may not use DeveloperHub for illegal or unauthorized purpose.
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
name: DeveloperHub
provenance_date: '2026-11-09'
provider_name: DeveloperHub
provider_slug: developerhub
slug: developerhub-eligibility
source_date: '2026-11-09'
source_filename: developerhub-eligibility.yml
source_heading: Eligibility
source_page: https://developerhub.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DeveloperHub\naid: developerhub\nurl: https://developerhub.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this agreement on behalf of a company or other legal entity, the terms “you” and\n    “your” shall refer to the entity.\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: You may not use DeveloperHub for illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years or older\
  \ to use DeveloperHub.\n"
source_yaml_url: https://artifacts.apis.io/developerhub/eligibility/developerhub-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from DeveloperHub's own page on 2026-11-09.
synthetic: false
tags:
- API Reference
- Developer Portal
- Documentation
- Knowledge Base
- OpenAPI
- Docs as Code
- MCP
- Agent Skills
---
