---
api_specs:
- filename: igrant-io-config-api-openapi.yml
  format: yaml
  label: iGrant.io Config API
  slug: igrant-io-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/igrant-io/openapi/igrant-io-config-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only businesses, bona fide charitable organisations, and other entities or persons located in Europe are eligible to apply for an iGrant.io Account under this Agreement.
    type: business
  - text: Only businesses, bona fide charitable organisations, and other entities or persons located in Europe are eligible to apply for an iGrant.io Account under this Agreement.
    type: nonprofit
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consent management only
    text: You may only use the Services to manage your Users’ consents.
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
name: iGrant.io
provenance_date: '2026-11-09'
provider_name: iGrant.io
provider_slug: igrant-io
slug: igrant-io-eligibility
source_date: '2026-11-09'
source_filename: igrant-io-eligibility.yml
source_heading: Eligibility
source_page: https://igrant.io/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iGrant.io\naid: igrant-io\nurl: https://igrant.io/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Only businesses, bona fide charitable organisations, and other entities or persons located in Europe are\n    eligible to apply for an iGrant.io Account under this Agreement.\n- type: nonprofit\n  text: Only businesses, bona fide charitable organisations, and other entities or persons located in Europe are\n    eligible to apply for an iGrant.io Account under this Agreement.\nrestricted_uses:\n- summary: Consent management only\n\
  \  text: You may only use the Services to manage your Users’ consents.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/igrant-io/eligibility/igrant-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from iGrant.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity
- Wallets
- eIDAS
---
