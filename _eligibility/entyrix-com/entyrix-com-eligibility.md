---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a natural or legal person who registers for and uses the Entyrix API service (the “User”)
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: using the Service for purposes contrary to Slovak or EU law (in particular the GDPR, Act No. 18/2018 Coll. and Act No. 211/2000 Coll.)
  - summary: Automated decisions without oversight
    text: automated decision-making with a significant effect on a data subject without human oversight (Art. 22 GDPR)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to authenticated endpoints requires a valid API key issued by the Provider.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: entyrix-com
provenance_date: '2026-11-09'
provider_name: entyrix-com
provider_slug: entyrix-com
slug: entyrix-com-eligibility
source_date: '2026-11-09'
source_filename: entyrix-com-eligibility.yml
source_heading: Eligibility
source_page: https://entyrix.com/api/v1/public/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: entyrix-com\naid: entyrix-com\nurl: https://entyrix.com/api/v1/public/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: a natural or legal person who registers for and uses the Entyrix API service (the “User”)\nrestricted_uses:\n- summary: Unlawful purposes\n  text: using the Service for purposes contrary to Slovak or EU law (in particular the GDPR, Act No. 18/2018 Coll.\n    and Act No. 211/2000 Coll.)\n- summary: Automated decisions without oversight\n  text: automated decision-making with a significant effect on a data subject without\
  \ human oversight (Art. 22 GDPR)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Access to authenticated endpoints requires a valid API key issued by the Provider.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/entyrix-com/eligibility/entyrix-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from entyrix-com's own page on 2026-11-09.
synthetic: false
tags:
- Business Data
- Compliance
- KYC
- European
---
