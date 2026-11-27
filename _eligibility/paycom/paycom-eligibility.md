---
claim_count: 2
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
  - summary: Use violating applicable laws
    text: You agree not to use the Site in any way which violates such laws or regulations.
  - summary: Commercial use
    text: You must not access or use for any commercial purposes any part of the Site or any services or materials available through the Site, unless permitted via written agreement between you and Paycom.
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
name: Paycom
provenance_date: '2026-11-10'
provider_name: Paycom
provider_slug: paycom
slug: paycom-eligibility
source_date: '2026-11-10'
source_filename: paycom-eligibility.yml
source_heading: Eligibility
source_page: https://www.paycom.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paycom\naid: paycom\nurl: https://www.paycom.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use violating applicable laws\n  text: You agree not to use the Site in any way which violates such laws or regulations.\n- summary: Commercial use\n  text: You must not access or use for any commercial purposes any part of the Site or any services or materials\n    available through the Site, unless permitted via written agreement between you and Paycom.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/paycom/eligibility/paycom-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Paycom's own page on 2026-11-10.
synthetic: false
tags:
- Human Resources
- Payroll
- HCM
- Software-as-a-Service
- Cloud
---
