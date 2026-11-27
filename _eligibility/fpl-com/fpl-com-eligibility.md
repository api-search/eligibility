---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Your bank account is with a U.S. bank, and you understand that your bank may charge for this service.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You are the bank account holder or an authorized agent for the bank account listed above.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Florida Power & Light
provenance_date: '2026-11-09'
provider_name: Florida Power & Light
provider_slug: fpl-com
slug: fpl-com-eligibility
source_date: '2026-11-09'
source_filename: fpl-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.fpl.com/account/bill/pay-online-terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Florida Power & Light\naid: fpl-com\nurl: https://www.fpl.com/account/bill/pay-online-terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Your bank account is with a U.S. bank, and you understand that your bank may charge for this service.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You are the bank account holder or an authorized agent for the bank account listed above.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fpl-com/eligibility/fpl-com-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from Florida Power & Light's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Electric Utility
- Energy
- Florida
- Utilities
---
