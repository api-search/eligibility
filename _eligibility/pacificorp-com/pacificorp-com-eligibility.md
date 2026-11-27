---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Some of the products and services described on this site may not be available in all states served by PacifiCorp
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As a security measure, access to certain areas of this site may require you to provide personally identifiable information to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PacifiCorp
provenance_date: '2026-11-10'
provider_name: PacifiCorp
provider_slug: pacificorp-com
slug: pacificorp-com-eligibility
source_date: '2026-11-10'
source_filename: pacificorp-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.pacificorp.com/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PacifiCorp\naid: pacificorp-com\nurl: https://www.pacificorp.com/terms-of-use.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Some of the products and services described on this site may not be available in all states served by PacifiCorp\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As a security measure, access to certain areas of this site may require you to provide personally identifiable\n    information to verify your identity.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pacificorp-com/eligibility/pacificorp-com-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from PacifiCorp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Energy
- Electric Utility
- Utilities
---
