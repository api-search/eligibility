---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By registering, you represent and warrant (a) that you are 18 years of age or over
    type: individual
  minimum_age:
    text: you are 18 years of age or over
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: you warrant that you will not use the Site for any purpose that is unlawful or prohibited by these Terms and Conditions.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Aluna may accept or reject registration requests for the Site in Aluna’s sole discretion
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aluna
provenance_date: '2026-11-09'
provider_name: Aluna
provider_slug: aluna
slug: aluna-eligibility
source_date: '2026-11-09'
source_filename: aluna-eligibility.yml
source_heading: Eligibility
source_page: https://alunacare.com/pages/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aluna\naid: aluna\nurl: https://alunacare.com/pages/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By registering, you represent and warrant (a) that you are 18 years of age or over\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: you warrant that you will not use the Site for any purpose that is unlawful or prohibited by these Terms\n    and Conditions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Aluna may accept or reject registration requests for the Site in\
  \ Aluna’s sole discretion\nminimum_age:\n  value: '18'\n  text: you are 18 years of age or over\n"
source_yaml_url: https://artifacts.apis.io/aluna/eligibility/aluna-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Aluna's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Respiratory
- Spirometry
- Remote Patient Monitoring
- Digital Health
- Medical Devices
- Asthma
- COPD
---
