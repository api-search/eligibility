---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Personal noncommercial use only
    text: solely for your own personal, noncommercial use
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
name: Resect AI
provenance_date: '2026-11-10'
provider_name: Resect AI
provider_slug: resect
slug: resect-eligibility
source_date: '2026-11-10'
source_filename: resect-eligibility.yml
source_heading: Eligibility
source_page: https://resect.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Resect AI\naid: resect\nurl: https://resect.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that\n    you represent)\nrestricted_uses:\n- summary: Personal noncommercial use only\n  text: solely for your own personal, noncommercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you may not access or use the Site or accept the Terms if you are not\
  \ at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/resect/eligibility/resect-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Resect AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Observability
- Accountability
- Machine Learning
---
