---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: The Service is available to individuals who are age 13 or over.
    type: individual
  minimum_age:
    text: The Service is available to individuals who are age 13 or over. If you are under the age of 13, you may not use the Service.
    value: '13'
  restricted_uses:
  - summary: No unlawful use
    text: You may not use the Service for any activity that constitutes, or encourages conduct that would constitute a criminal offense, give rise to civil liability, or otherwise violate any applicable law.
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
name: Myndlift
provenance_date: '2026-11-10'
provider_name: Myndlift
provider_slug: myndlift
slug: myndlift-eligibility
source_date: '2026-11-10'
source_filename: myndlift-eligibility.yml
source_heading: Eligibility
source_page: https://www.myndlift.com/terms-of-service-individuals
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Myndlift\naid: myndlift\nurl: https://www.myndlift.com/terms-of-service-individuals\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government\n    embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: The Service is available to individuals who are age 13 or over.\nrestricted_uses:\n- summary: No unlawful use\n  text: You may not use the Service for any activity that constitutes, or encourages conduct\
  \ that would constitute\n    a criminal offense, give rise to civil liability, or otherwise violate any applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Service is available to individuals who are age 13 or over. If you are under the age of 13, you may\n    not use the Service.\n"
source_yaml_url: https://artifacts.apis.io/myndlift/eligibility/myndlift-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Myndlift's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Neurofeedback
- Mental Health
- Digital Health
- EEG
- Brain Training
- Wearables
- Telehealth
---
