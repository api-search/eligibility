---
api_specs:
- filename: normapi-com-openapi.yml
  format: yaml
  label: NormAPI REST API
  slug: normapi-rest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/normapi-com/openapi/normapi-com-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The offering is directed exclusively at businesses (Unternehmer within the meaning of § 14 BGB); contracts with consumers are excluded.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful content
    text: submitting unlawful content
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Any business can create an account itself; no invitation is required.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NormAPI
provenance_date: '2026-11-10'
provider_name: NormAPI
provider_slug: normapi-com
slug: normapi-com-eligibility
source_date: '2026-11-10'
source_filename: normapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://normapi.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NormAPI\naid: normapi-com\nurl: https://normapi.com/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The offering is directed exclusively at businesses (Unternehmer within the meaning of § 14 BGB); contracts\n    with consumers are excluded.\nrestricted_uses:\n- summary: Unlawful content\n  text: submitting unlawful content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Any business can create an account itself; no invitation is required.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/normapi-com/eligibility/normapi-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from NormAPI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Invoicing
- XRechnung
- ZUGFeRD
- Germany
---
