---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Services are not for use by anyone under the age of 16.
    value: '16'
  restricted_uses:
  - summary: No reselling access
    text: Rent, lease, loan, trade, sell/re-sell access to the Services or related data;
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
name: Brandyourself
provenance_date: '2026-11-09'
provider_name: Brandyourself
provider_slug: brandyourself
slug: brandyourself-eligibility
source_date: '2026-11-09'
source_filename: brandyourself-eligibility.yml
source_heading: Eligibility
source_page: https://brandyourself.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brandyourself\naid: brandyourself\nurl: https://brandyourself.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No reselling access\n  text: Rent, lease, loan, trade, sell/re-sell access to the Services or related data;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Services are not for use by anyone under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/brandyourself/eligibility/brandyourself-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Brandyourself's own page on 2026-11-09.
synthetic: false
tags:
- Reputation
- Privacy
- Software-as-a-Service
- BrandYourself
---
