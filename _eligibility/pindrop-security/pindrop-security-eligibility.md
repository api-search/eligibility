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
  - summary: Unlawful use and impersonation
    text: To impersonate or attempt to impersonate the Company, a Company employee, another user or any other person or entity
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
name: Pindrop Security
provenance_date: '2026-11-10'
provider_name: Pindrop Security
provider_slug: pindrop-security
slug: pindrop-security-eligibility
source_date: '2026-11-10'
source_filename: pindrop-security-eligibility.yml
source_heading: Eligibility
source_page: https://www.pindrop.com/legal/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pindrop Security\naid: pindrop-security\nurl: https://www.pindrop.com/legal/website-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use and impersonation\n  text: To impersonate or attempt to impersonate the Company, a Company employee, another user or any other person\n    or entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pindrop-security/eligibility/pindrop-security-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Pindrop Security's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Voice
- Authentication
- Fraud Prevention
- Deepfake Detection
- Identity
- Biometrics
- Contact Center
---
