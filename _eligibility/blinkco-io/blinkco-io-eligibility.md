---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are entering into this TOS on behalf of a company or other legal entity, You represent that You have the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitors in similar business
    text: If the Customer operates in a similar business to ours, we reserve the right to refuse to offer our Services to them.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Blink may agree or deny service to any person or company without any prior notice
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Blink
provenance_date: '2026-11-09'
provider_name: Blink
provider_slug: blinkco-io
slug: blinkco-io-eligibility
source_date: '2026-11-09'
source_filename: blinkco-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.blinkco.io/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blink\naid: blinkco-io\nurl: https://www.blinkco.io/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are entering into this TOS on behalf of a company or other legal entity, You represent that You have\n    the authority to bind such entity\nrestricted_uses:\n- summary: Competitors in similar business\n  text: If the Customer operates in a similar business to ours, we reserve the right to refuse to offer our Services\n    to them.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text:\
  \ Blink may agree or deny service to any person or company without any prior notice\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blinkco-io/eligibility/blinkco-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Blink's own page on 2026-11-09.
synthetic: false
tags:
- Company
- IoT
- Security
- Smart Home
- Cloud
---
