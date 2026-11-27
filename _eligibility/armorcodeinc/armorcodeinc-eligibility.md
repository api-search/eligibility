---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are acting on behalf of your employer or another entity, you represent and warrant that you are authorized to bind such employer or entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Armorcodeinc
provenance_date: '2026-11-09'
provider_name: Armorcodeinc
provider_slug: armorcodeinc
slug: armorcodeinc-eligibility
source_date: '2026-11-09'
source_filename: armorcodeinc-eligibility.yml
source_heading: Eligibility
source_page: https://www.armorcode.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Armorcodeinc\naid: armorcodeinc\nurl: https://www.armorcode.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are acting on behalf of your employer or another entity, you represent and warrant that you are authorized\n    to bind such employer or entity to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/armorcodeinc/eligibility/armorcodeinc-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Armorcodeinc's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Artificial Intelligence
- Risk Management
- Exposure Management
---
