---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Membership in any Adgager panel is open and free to individuals (not companies or other commercial entities) who are at least fourteen (14) years old or meet the minimum age requirement in their geographic location.
    type: individual
  - text: Membership in any Adgager panel is open and free to individuals (not companies or other commercial entities)
    type: business
  minimum_age:
    text: at least fourteen (14) years old or meet the minimum age requirement in their geographic location
    value: '14'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: Use the Site only for your personal, non-commercial use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We ask you to verify your email and phone number to confirm your unique user identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Adgager
provenance_date: '2026-11-09'
provider_name: Adgager
provider_slug: adgager
slug: adgager-eligibility
source_date: '2026-11-09'
source_filename: adgager-eligibility.yml
source_heading: Eligibility
source_page: https://www.adgager.com/en/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adgager\naid: adgager\nurl: https://www.adgager.com/en/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Membership in any Adgager panel is open and free to individuals (not companies or other commercial entities)\n    who are at least fourteen (14) years old or meet the minimum age requirement in their geographic location.\n- type: business\n  text: Membership in any Adgager panel is open and free to individuals (not companies or other commercial entities)\nrestricted_uses:\n- summary: Non-commercial personal use only\n\
  \  text: Use the Site only for your personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We ask you to verify your email and phone number to confirm your unique user identity.\nminimum_age:\n  value: '14'\n  text: at least fourteen (14) years old or meet the minimum age requirement in their geographic location\n"
source_yaml_url: https://artifacts.apis.io/adgager/eligibility/adgager-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Adgager's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Market Research
- Consumer Insights
- Surveys
- Advertising
- Advertising Effectiveness
- Brand Measurement
- Panel
- GraphQL
- Turkey
---
