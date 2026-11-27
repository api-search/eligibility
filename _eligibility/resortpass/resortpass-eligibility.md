---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: are 18 years of age or older to use the Site
    type: individual
  - text: A Referrer must be a natural person and cannot be a business, partnership, trust, or other legal entity.
    type: business
  minimum_age:
    text: are 18 years of age or older to use the Site
    value: '18'
  restricted_uses:
  - summary: Collecting personal information via Services
    text: using the Sites or the Services to access or collect any personally identifiable information
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
name: ResortPass
provenance_date: '2026-11-10'
provider_name: ResortPass
provider_slug: resortpass
slug: resortpass-eligibility
source_date: '2026-11-10'
source_filename: resortpass-eligibility.yml
source_heading: Eligibility
source_page: https://www.resortpass.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ResortPass\naid: resortpass\nurl: https://www.resortpass.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: are 18 years of age or older to use the Site\n- type: business\n  text: A Referrer must be a natural person and cannot be a business, partnership, trust, or other legal entity.\nrestricted_uses:\n- summary: Collecting personal information via Services\n  text: using the Sites or the Services to access or collect any personally identifiable information\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: are 18 years of age or older to use the Site\n"
source_yaml_url: https://artifacts.apis.io/resortpass/eligibility/resortpass-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ResortPass's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Travel
- Hospitality
- Hotels
- Booking
- Marketplace
- Leisure
---
