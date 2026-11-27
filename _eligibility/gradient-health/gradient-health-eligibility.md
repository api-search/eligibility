---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CN
    - CU
    - IR
    - KP
    - RU
    - VE
    served: []
    text: Customer is explicitly prohibited from transferring any Data to, or permitting any person or entity to access any Data from, any country that is subject to legal or commercial sanctions imposed by the United States, or any "country of concern" ... which as of the Last Updated Date comprise the People's Republic of China (including Hong Kong and Macau), Cuba, Iran, North Korea, Russia, and Venezuela
  entity_types:
  - text: By using the Service, you represent and warrant that you are of legal age to form a binding contract with Gradient
    type: individual
  - text: If you register and use the Service on behalf of another entity or third party, you must have the proper authority to register, use the Service, and bind the entity or third party
    type: business
  minimum_age:
    text: you represent and warrant that you are of legal age to form a binding contract with Gradient
    value: null
  restricted_uses:
  - summary: No patient marketing, claim adjustment or discrimination uses
    text: you are not permitted to use any Gradient Data to further any projects or technologies that are intended or created to target patient marketing; adjust or reject health insurance claims; discriminate against patients with pre-existing disease or other protected status; identify individuals
  - summary: Sanctioned countries and covered persons
    text: 'Customer is explicitly prohibited from, directly or indirectly: (1) transferring any Data to, or permitting any person or entity to access any Data from, any country that is subject to legal or commercial sanctions imposed by the United States'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CN
- CU
- IR
- KP
- RU
- VE
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Gradient Health
provenance_date: '2026-11-09'
provider_name: Gradient Health
provider_slug: gradient-health
slug: gradient-health-eligibility
source_date: '2026-11-09'
source_filename: gradient-health-eligibility.yml
source_heading: Eligibility
source_page: https://gradienthealth.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gradient Health\naid: gradient-health\nurl: https://gradienthealth.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CN\n  - CU\n  - IR\n  - KP\n  - RU\n  - VE\n  text: Customer is explicitly prohibited from transferring any Data to, or permitting any person or entity to access\n    any Data from, any country that is subject to legal or commercial sanctions imposed by the United States, or\n    any \"country of concern\" ... which as of the Last Updated Date comprise the People's Republic of China (including\n    Hong Kong and Macau), Cuba, Iran, North Korea, Russia, and Venezuela\n\
  entity_types:\n- type: individual\n  text: By using the Service, you represent and warrant that you are of legal age to form a binding contract with\n    Gradient\n- type: business\n  text: If you register and use the Service on behalf of another entity or third party, you must have the proper\n    authority to register, use the Service, and bind the entity or third party\nrestricted_uses:\n- summary: No patient marketing, claim adjustment or discrimination uses\n  text: you are not permitted to use any Gradient Data to further any projects or technologies that are intended\n    or created to target patient marketing; adjust or reject health insurance claims; discriminate against patients\n    with pre-existing disease or other protected status; identify individuals\n- summary: Sanctioned countries and covered persons\n  text: 'Customer is explicitly prohibited from, directly or indirectly: (1) transferring any Data to, or permitting\n    any person or entity to access any Data from, any\
  \ country that is subject to legal or commercial sanctions imposed\n    by the United States'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you represent and warrant that you are of legal age to form a binding contract with Gradient\n"
source_yaml_url: https://artifacts.apis.io/gradient-health/eligibility/gradient-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Gradient Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Medical Imaging
- Healthcare Data
- Health AI
- DICOM
- Machine Learning
- Data Platform
- Radiology
---
