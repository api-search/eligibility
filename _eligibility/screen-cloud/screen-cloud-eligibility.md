---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If You are based in North or South America, your agreement is with ScreenCloud Inc, a Delaware Company
  entity_types:
  - text: If You are accepting these Terms on behalf of a company or other legal entity, You warrant that You are authorised to enter into legally binding contracts on behalf of said entity.
    type: business
  minimum_age:
    text: You warrant that all users of the Customer Account are at least 18 years old
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
name: ScreenCloud
provenance_date: '2026-11-10'
provider_name: ScreenCloud
provider_slug: screen-cloud
slug: screen-cloud-eligibility
source_date: '2026-11-10'
source_filename: screen-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://screencloud.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ScreenCloud\naid: screen-cloud\nurl: https://screencloud.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If You are based in North or South America, your agreement is with ScreenCloud Inc, a Delaware Company\nentity_types:\n- type: business\n  text: If You are accepting these Terms on behalf of a company or other legal entity, You warrant that You are\n    authorised to enter into legally binding contracts on behalf of said entity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ You warrant that all users of the Customer Account are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/screen-cloud/eligibility/screen-cloud-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from ScreenCloud's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Signage
- Software-as-a-Service
- Cloud
- Marketing
---
