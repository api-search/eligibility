---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing the Sites for or on behalf of a company, entity, or organization, you also represent and warrant that you are its authorized representative
    type: business
  minimum_age:
    text: You represent and warrant that you are over 18 years of age
    value: '18'
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
name: Innovid
provenance_date: '2026-11-09'
provider_name: Innovid
provider_slug: innovid
slug: innovid-eligibility
source_date: '2026-11-09'
source_filename: innovid-eligibility.yml
source_heading: Eligibility
source_page: https://www.innovid.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Innovid\naid: innovid\nurl: https://www.innovid.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing the Sites for or on behalf of a company, entity, or organization, you also represent\n    and warrant that you are its authorized representative\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are over 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/innovid/eligibility/innovid-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Innovid's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- Marketing
- Video
- Software-as-a-Service
---
