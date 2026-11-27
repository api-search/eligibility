---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are of legal age to form a binding contract
    type: individual
  - text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization or entity's behalf
    type: business
  minimum_age:
    text: You represent and warrant that you are of legal age to form a binding contract (or if not, you've received your parent's or guardian's permission to use the Website
    value: null
  restricted_uses:
  - summary: Use must comply with applicable law
    text: If your use of the Website is prohibited by applicable laws, then you aren't authorized to use the Website.
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
name: Ordr
provenance_date: '2026-11-10'
provider_name: Ordr
provider_slug: ordr
slug: ordr-eligibility
source_date: '2026-11-10'
source_filename: ordr-eligibility.yml
source_heading: Eligibility
source_page: https://ordr.net/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ordr\naid: ordr\nurl: https://ordr.net/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are of legal age to form a binding contract\n- type: business\n  text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization or entity's behalf\nrestricted_uses:\n- summary: Use must comply with applicable law\n  text: If your use of the Website is prohibited by applicable laws, then\
  \ you aren't authorized to use the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent and warrant that you are of legal age to form a binding contract (or if not, you've received\n    your parent's or guardian's permission to use the Website\n"
source_yaml_url: https://artifacts.apis.io/ordr/eligibility/ordr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ordr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Connected Device Security
- IoT
- OT Security
- IoMT
- Asset Intelligence
- CAASM
- Healthcare
- Network Segmentation
---
