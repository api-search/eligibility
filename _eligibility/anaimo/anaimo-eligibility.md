---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: In the event that some of our services are specifically aimed at minors, ANAIMO SPAIN, S.L. will request the consent of parents or guardians
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The completion of the registration form is mandatory to access and enjoy certain services offered on the web.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Anaimo
provenance_date: '2026-11-09'
provider_name: Anaimo
provider_slug: anaimo
slug: anaimo-eligibility
source_date: '2026-11-09'
source_filename: anaimo-eligibility.yml
source_heading: Eligibility
source_page: https://anaimo.com/aviso-legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anaimo\naid: anaimo\nurl: https://anaimo.com/aviso-legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The completion of the registration form is mandatory to access and enjoy certain services offered on the\n    web.\nminimum_age:\n  value: null\n  text: In the event that some of our services are specifically aimed at minors, ANAIMO SPAIN, S.L. will request\n    the consent of parents or guardians\n"
source_yaml_url: https://artifacts.apis.io/anaimo/eligibility/anaimo-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from Anaimo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automation
- Virtual Assistant
- Retail
---
