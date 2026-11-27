---
api_specs:
- filename: omniaauto-ca-openapi.json
  format: json
  label: OmniaAuto API
  slug: omniaauto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omniaauto-ca/openapi/omniaauto-ca-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing on behalf of a company, you represent that you may bind that company.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal use only for snapshots
    text: Snapshots are licensed for your organization's own internal use
  - summary: Feed license tied to registered IPs
    text: Your Feed key is pinned to those IP(s) .
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
name: omniaauto-ca
provenance_date: '2026-11-10'
provider_name: omniaauto-ca
provider_slug: omniaauto-ca
slug: omniaauto-ca-eligibility
source_date: '2026-11-10'
source_filename: omniaauto-ca-eligibility.yml
source_heading: Eligibility
source_page: https://omniaauto.ca/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: omniaauto-ca\naid: omniaauto-ca\nurl: https://omniaauto.ca/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing on behalf of a company, you represent that you may bind that company.\nrestricted_uses:\n- summary: Internal use only for snapshots\n  text: Snapshots are licensed for your organization's own internal use\n- summary: Feed license tied to registered IPs\n  text: Your Feed key is pinned to those IP(s) .\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/omniaauto-ca/eligibility/omniaauto-ca-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from omniaauto-ca's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automotive
- Data
- Markets
---
