---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you certify that you are at least 18 years old, or if you are under 18 years old, your parent or legal guardian has reviewed the terms and accepted them on your behalf.
    value: '18'
  restricted_uses:
  - summary: Prohibited conduct on the site
    text: 'You agree that you will not use the site or any site materials, project, or service to: (a) transmit spam, bulk, or unsolicited communications'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You agree to provide true, accurate, current and complete information about yourself as prompted by the site's registration form
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: oreilly-com
provenance_date: '2026-11-10'
provider_name: oreilly-com
provider_slug: oreilly-com
slug: oreilly-com-eligibility
source_date: '2026-11-10'
source_filename: oreilly-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.oreilly.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: oreilly-com\naid: oreilly-com\nurl: https://www.oreilly.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited conduct on the site\n  text: 'You agree that you will not use the site or any site materials, project, or service to: (a) transmit spam,\n    bulk, or unsolicited communications'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You agree to provide true, accurate, current and complete information about yourself as prompted by the\n    site's registration form\nminimum_age:\n \
  \ value: '18'\n  text: you certify that you are at least 18 years old, or if you are under 18 years old, your parent or legal guardian\n    has reviewed the terms and accepted them on your behalf.\n"
source_yaml_url: https://artifacts.apis.io/oreilly-com/eligibility/oreilly-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from oreilly-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- Technology
- Training
- Publishing
---
