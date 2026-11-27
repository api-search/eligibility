---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is built for businesses that advertise on Meta.
    type: business
  - text: A "consumer" is an individual using it mainly for personal purposes outside any trade, business or profession.
    type: individual
  minimum_age:
    text: You must be at least 18
    value: '18'
  restricted_uses:
  - summary: Fraudulent or misleading ads
    text: Create fraudulent or misleading ads
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
name: Ads Uploader
provenance_date: '2026-11-09'
provider_name: Ads Uploader
provider_slug: adsuploader-com
slug: adsuploader-com-eligibility
source_date: '2026-11-09'
source_filename: adsuploader-com-eligibility.yml
source_heading: Eligibility
source_page: https://adsuploader.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ads Uploader\naid: adsuploader-com\nurl: https://adsuploader.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is built for businesses that advertise on Meta.\n- type: individual\n  text: A \"consumer\" is an individual using it mainly for personal purposes outside any trade, business or profession.\nrestricted_uses:\n- summary: Fraudulent or misleading ads\n  text: Create fraudulent or misleading ads\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: You must be at least 18\n"
source_yaml_url: https://artifacts.apis.io/adsuploader-com/eligibility/adsuploader-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ads Uploader's own page on 2026-11-09.
synthetic: false
tags:
- Meta Ads
- Automation
- Bulk Upload
- Creative Testing
- Marketing
---
