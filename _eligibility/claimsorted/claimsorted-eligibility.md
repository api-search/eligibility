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
  - summary: No fraud or illegal use
    text: Use the ClaimSorted Services, Website, or Apps for unauthorised or illegal purposes, including uploading viruses, malware, or other harmful software.
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
name: ClaimSorted
provenance_date: '2026-11-09'
provider_name: ClaimSorted
provider_slug: claimsorted
slug: claimsorted-eligibility
source_date: '2026-11-09'
source_filename: claimsorted-eligibility.yml
source_heading: Eligibility
source_page: https://claimsorted.com:443/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClaimSorted\naid: claimsorted\nurl: https://claimsorted.com:443/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No fraud or illegal use\n  text: Use the ClaimSorted Services, Website, or Apps for unauthorised or illegal purposes, including uploading\n    viruses, malware, or other harmful software.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/claimsorted/eligibility/claimsorted-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from ClaimSorted's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurtech
- Insurance
- Claims
- Claims Management
- Third-Party Administrator
- Fraud Prevention
---
