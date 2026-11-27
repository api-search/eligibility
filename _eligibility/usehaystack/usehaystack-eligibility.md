---
api_specs:
- filename: usehaystack-openapi-generated.yml
  format: yaml
  label: Haystack Analytics API
  slug: usehaystack-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usehaystack/openapi/_ae-authored/usehaystack-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Haystack business plan you purchase, register for, order, or renew
    type: business
  minimum_age:
    text: You are over the age of 16 as all portions of the Platform are intended for only individuals over 16.
    value: '16'
  restricted_uses:
  - summary: No spam or unsolicited promotion
    text: use any portion of the Platform to aid in transmitting, or procure the sending of, any advertising or promotional material
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
name: Haystack Analytics
provenance_date: '2026-11-10'
provider_name: Haystack Analytics
provider_slug: usehaystack
slug: usehaystack-eligibility
source_date: '2026-11-10'
source_filename: usehaystack-eligibility.yml
source_heading: Eligibility
source_page: https://www.usehaystack.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Haystack Analytics\naid: usehaystack\nurl: https://www.usehaystack.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Haystack business plan you purchase, register for, order, or renew\nrestricted_uses:\n- summary: No spam or unsolicited promotion\n  text: use any portion of the Platform to aid in transmitting, or procure the sending of, any advertising or promotional\n    material\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You are over the age of\
  \ 16 as all portions of the Platform are intended for only individuals over 16.\n"
source_yaml_url: https://artifacts.apis.io/usehaystack/eligibility/usehaystack-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Haystack Analytics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- DeliveryOps
- Product Management
- Engineering
- Analytics
---
