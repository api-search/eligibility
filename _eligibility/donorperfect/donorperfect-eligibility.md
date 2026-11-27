---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: For markets outside of the United States and Canada, our services are provided on a best-effort basis and are governed by the regulatory frameworks of the U.S. and Canada.
  entity_types:
  - text: you, or the organization that you represent
    type: other
  minimum_age:
    text: The Services are available to users who are 18 years of age or older.
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
name: DonorPerfect
provenance_date: '2026-11-09'
provider_name: DonorPerfect
provider_slug: donorperfect
slug: donorperfect-eligibility
source_date: '2026-11-09'
source_filename: donorperfect-eligibility.yml
source_heading: Eligibility
source_page: https://www.donorperfect.com:443/company/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DonorPerfect\naid: donorperfect\nurl: https://www.donorperfect.com:443/company/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: For markets outside of the United States and Canada, our services are provided on a best-effort basis and\n    are governed by the regulatory frameworks of the U.S. and Canada.\nentity_types:\n- type: other\n  text: you, or the organization that you represent\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are available to users who\
  \ are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/donorperfect/eligibility/donorperfect-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from DonorPerfect's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fundraising
- Non-Profit
- CRM
- Software
---
