---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is solely for use by businesses conducting operations in the United States.
  entity_types:
  - text: The Service is solely for use by businesses conducting operations in the United States.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Marketing communications without consent
    text: You will not use the Service to send communications to any individual who has not provided appropriate consent or who has opted out of receiving such communications
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
name: Arch
provenance_date: '2026-11-09'
provider_name: Arch
provider_slug: getarch-com
slug: getarch-com-eligibility
source_date: '2026-11-09'
source_filename: getarch-com-eligibility.yml
source_heading: Eligibility
source_page: https://getarch.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arch\naid: getarch-com\nurl: https://getarch.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is solely for use by businesses conducting operations in the United States.\nentity_types:\n- type: business\n  text: The Service is solely for use by businesses conducting operations in the United States.\nrestricted_uses:\n- summary: Marketing communications without consent\n  text: You will not use the Service to send communications to any individual who has not provided appropriate consent\n    or who has opted out of receiving such communications\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/getarch-com/eligibility/getarch-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Arch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Marketing
- Home Services
- ServiceTitan
---
