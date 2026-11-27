---
api_specs:
- filename: agentage-io-openapi-generated.yml
  format: yaml
  label: agentage-io API
  slug: agentage-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentage-io/openapi/_ae-authored/agentage-io-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: Do not use the Service to break the law, infringe others’ rights, attempt to disrupt or gain unauthorized access to the system, or store content you have no right to store.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in through a third-party provider (GitHub, Google, or Microsoft).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: agentage-io
provenance_date: '2026-11-09'
provider_name: agentage-io
provider_slug: agentage-io
slug: agentage-io-eligibility
source_date: '2026-11-09'
source_filename: agentage-io-eligibility.yml
source_heading: Eligibility
source_page: https://agentage.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: agentage-io\naid: agentage-io\nurl: https://agentage.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: Do not use the Service to break the law, infringe others’ rights, attempt to disrupt or gain unauthorized\n    access to the system, or store content you have no right to store.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in through a third-party provider (GitHub, Google, or Microsoft).\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentage-io/eligibility/agentage-io-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from agentage-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Memory
- Collaboration
- Privacy
- EU-hosted
---
