---
api_specs:
- filename: artifacta-io-openapi.json
  format: json
  label: Artifacta API
  slug: artifacta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artifacta-io/openapi/artifacta-io-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you’re using Artifacta on behalf of an organization, you confirm you have authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export-control and illegal content restrictions
    text: Store or transmit content that is illegal, infringes third-party rights, or violates export-control laws.
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
name: Artifacta
provenance_date: '2026-11-09'
provider_name: Artifacta
provider_slug: artifacta-io
slug: artifacta-io-eligibility
source_date: '2026-11-09'
source_filename: artifacta-io-eligibility.yml
source_heading: Eligibility
source_page: https://artifacta.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Artifacta\naid: artifacta-io\nurl: https://artifacta.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you’re using Artifacta on behalf of an organization, you confirm you have authority to bind that organization.\nrestricted_uses:\n- summary: Export-control and illegal content restrictions\n  text: Store or transmit content that is illegal, infringes third-party rights, or violates export-control laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/artifacta-io/eligibility/artifacta-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Artifacta's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Storage
- Artifact
- MCP
- Open Source
---
