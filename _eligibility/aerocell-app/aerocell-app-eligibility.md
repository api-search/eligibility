---
api_specs:
- filename: aerocell-app-api-openapi.json
  format: json
  label: 'AeroCell: Affordable eSIMs — Read-only API API'
  slug: aerocell-affordable-esims-read-only-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aerocell-app/openapi/_original/aerocell-app-api-openapi.json
claim_count: 1
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
  - summary: Sanctions-restricted activity
    text: You may not use the services for unlawful, abusive, fraudulent, network-disruptive, resale, bulk provisioning, SIM-box, telecommunications manipulation, rights-infringing, or sanctions-restricted activity.
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
name: AeroCell
provenance_date: '2026-11-09'
provider_name: AeroCell
provider_slug: aerocell-app
slug: aerocell-app-eligibility
source_date: '2026-11-09'
source_filename: aerocell-app-eligibility.yml
source_heading: Eligibility
source_page: https://aerocell.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AeroCell\naid: aerocell-app\nurl: https://aerocell.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sanctions-restricted activity\n  text: You may not use the services for unlawful, abusive, fraudulent, network-disruptive, resale, bulk provisioning,\n    SIM-box, telecommunications manipulation, rights-infringing, or sanctions-restricted activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aerocell-app/eligibility/aerocell-app-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AeroCell's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- eSIM
- Mobile Data
- International
- Connectivity
- Telecommunications
---
