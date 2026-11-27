---
api_specs:
- filename: worklytics-openapi-generated.yml
  format: yaml
  label: Worklytics API
  slug: worklytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklytics/openapi/_ae-authored/worklytics-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an organization, the individual who agrees to this Agreement on your behalf must have the authority to bind you to the Agreement
    type: business
  - text: When you create an account with us, you guarantee that you are above the age of 18
    type: individual
  minimum_age:
    text: When you create an account with us, you guarantee that you are above the age of 18
    value: '18'
  restricted_uses:
  - summary: Offensive or unlawful usernames
    text: You may not use as a username any name that is offensive, vulgar or obscene.
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
name: Worklytics
provenance_date: '2026-11-10'
provider_name: Worklytics
provider_slug: worklytics
slug: worklytics-eligibility
source_date: '2026-11-10'
source_filename: worklytics-eligibility.yml
source_heading: Eligibility
source_page: https://www.worklytics.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Worklytics\naid: worklytics\nurl: https://www.worklytics.co/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are an organization, the individual who agrees to this Agreement on your behalf must have the authority\n    to bind you to the Agreement\n- type: individual\n  text: When you create an account with us, you guarantee that you are above the age of 18\nrestricted_uses:\n- summary: Offensive or unlawful usernames\n  text: You may not use as a username any name that is offensive, vulgar or obscene.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When you create an account with us, you guarantee that you are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/worklytics/eligibility/worklytics-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Worklytics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Analytics
- Workplace
- Artificial Intelligence
- Productivity
---
