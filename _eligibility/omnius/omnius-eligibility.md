---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These GTC only apply if the respective business partner is an entrepreneur within the meaning of § 14 BGB (German Civil Code) or a legal entity under public law.
    type: business
  - text: These GTC only apply if the respective business partner is an entrepreneur within the meaning of § 14 BGB (German Civil Code) or a legal entity under public law.
    type: government
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
name: Omnius
provenance_date: '2026-11-10'
provider_name: Omnius
provider_slug: omnius
slug: omnius-eligibility
source_date: '2026-11-10'
source_filename: omnius-eligibility.yml
source_heading: Eligibility
source_page: https://omnius.com/legal/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Omnius\naid: omnius\nurl: https://omnius.com/legal/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These GTC only apply if the respective business partner is an entrepreneur within the meaning of § 14 BGB\n    (German Civil Code) or a legal entity under public law.\n- type: government\n  text: These GTC only apply if the respective business partner is an entrepreneur within the meaning of § 14 BGB\n    (German Civil Code) or a legal entity under public law.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/omnius/eligibility/omnius-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Omnius's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Claims Automation
- Artificial Intelligence
- AI Agents
- Document Processing
- Machine Learning
---
