---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Porsche operates the Developer Portal for businesses only and does not accept a use of the Developer Portal by consumers within the meaning of Section 13 of the German Civil Code
    type: business
  - text: as an individual You are lawfully able and have the capacity to enter into contracts
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or harmful applications
    text: using the Developer Portal to promote or operate illegal activities, including any applications with racist, xenophobic, violent, pornographic, immoral or inhumane contents
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Porsche may reject Account registration requests without providing any reasons.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Porsche
provenance_date: '2026-11-10'
provider_name: Porsche
provider_slug: porsche
slug: porsche-eligibility
source_date: '2026-11-10'
source_filename: porsche-eligibility.yml
source_heading: Eligibility
source_page: https://developer.porsche.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Porsche\naid: porsche\nurl: https://developer.porsche.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Porsche operates the Developer Portal for businesses only and does not accept a use of the Developer Portal\n    by consumers within the meaning of Section 13 of the German Civil Code\n- type: individual\n  text: as an individual You are lawfully able and have the capacity to enter into contracts\nrestricted_uses:\n- summary: Illegal or harmful applications\n  text: using the Developer Portal to promote or operate illegal activities,\
  \ including any applications with racist,\n    xenophobic, violent, pornographic, immoral or inhumane contents\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Porsche may reject Account registration requests without providing any reasons.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/porsche/eligibility/porsche-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Porsche's own page on 2026-11-10.
synthetic: false
tags:
- Automobiles
- Cars
- Vehicles
- Automotive
- Connected Vehicles
- Identity
- Design Systems
- Open Source
- Germany
---
