---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Website is available for individuals aged 18 years or older.
    type: individual
  - text: If you are accepting the Agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to the terms and conditions contained herein.
    type: business
  minimum_age:
    text: This Website is available for individuals aged 18 years or older.
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
name: TMRW Life Sciences *
provenance_date: '2026-11-10'
provider_name: TMRW Life Sciences *
provider_slug: tmrw-life-sciences
slug: tmrw-life-sciences-eligibility
source_date: '2026-11-10'
source_filename: tmrw-life-sciences-eligibility.yml
source_heading: Eligibility
source_page: https://www.tmrwlifesciences.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TMRW Life Sciences *\naid: tmrw-life-sciences\nurl: https://www.tmrwlifesciences.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Website is available for individuals aged 18 years or older.\n- type: business\n  text: If you are accepting the Agreement on behalf of a company or other legal entity, you represent that you\n    have the authority to bind such entity to the terms and conditions contained herein.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: This Website is available for individuals aged 18 years or older.\n"
source_yaml_url: https://artifacts.apis.io/tmrw-life-sciences/eligibility/tmrw-life-sciences-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from TMRW Life Sciences *'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Fertility
- IVF
- Healthcare
- Medical Devices
- Cryostorage
- Biotechnology
- Automation
- Diagnostics
- Therapeutics
- Artificial Intelligence
---
