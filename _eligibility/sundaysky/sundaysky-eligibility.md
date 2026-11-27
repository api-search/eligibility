---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted Data
    text: Customer will ensure that the Customer Data does not contain any highly sensitive information that is subject to laws or regulations that impose increased protections
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
name: SundaySky
provenance_date: '2026-11-10'
provider_name: SundaySky
provider_slug: sundaysky
slug: sundaysky-eligibility
source_date: '2026-11-10'
source_filename: sundaysky-eligibility.yml
source_heading: Eligibility
source_page: https://sundaysky.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SundaySky\naid: sundaysky\nurl: https://sundaysky.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Restricted Data\n  text: Customer will ensure that the Customer Data does not contain any highly sensitive information that is subject\n    to laws or regulations that impose increased protections\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sundaysky/eligibility/sundaysky-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from SundaySky's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Personalization
- Video Personalization
- Marketing
- Customer Experience
- Artificial Intelligence
- Enterprise
- Video Generation
- Media
- Analytics
- MarTech
---
