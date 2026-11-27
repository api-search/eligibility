---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Products are offered for business use only.
    type: business
  - text: You may use the Website and accept these Terms only if you are at least 18 years of age and competent to contract under the Indian Contract Act, 1872.
    type: individual
  minimum_age:
    text: at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No personal or consumer use
    text: They are not intended for personal, household or consumer use.
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
name: COSGrid Networks
provenance_date: '2026-11-09'
provider_name: COSGrid Networks
provider_slug: cosgrid
slug: cosgrid-eligibility
source_date: '2026-11-09'
source_filename: cosgrid-eligibility.yml
source_heading: Eligibility
source_page: https://www.cosgrid.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: COSGrid Networks\naid: cosgrid\nurl: https://www.cosgrid.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Products are offered for business use only.\n- type: individual\n  text: You may use the Website and accept these Terms only if you are at least 18 years of age and competent to\n    contract under the Indian Contract Act, 1872.\nrestricted_uses:\n- summary: No personal or consumer use\n  text: They are not intended for personal, household or consumer use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/cosgrid/eligibility/cosgrid-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from COSGrid Networks's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Zero Trust
- SD-WAN
- Cloud Security
---
