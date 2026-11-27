---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Pharmacy Site: any individual physical store or online entity or any other entity approved by Healthera whose business is to dispense medications'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful material
    text: 'The Customer shall not access, store, distribute or transmit any Viruses, or any material during the course of its use of the Services that: 2.5.1 is unlawful, harmful, threatening, defamatory, obscene, infringing, harassing or racially or ethnically offensive'
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
name: Healthera
provenance_date: '2026-11-09'
provider_name: Healthera
provider_slug: healthera
slug: healthera-eligibility
source_date: '2026-11-09'
source_filename: healthera-eligibility.yml
source_heading: Eligibility
source_page: https://healthera.co.uk/pharmacy-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Healthera\naid: healthera\nurl: https://healthera.co.uk/pharmacy-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'Pharmacy Site: any individual physical store or online entity or any other entity approved by Healthera\n    whose business is to dispense medications'\nrestricted_uses:\n- summary: Unlawful or harmful material\n  text: 'The Customer shall not access, store, distribute or transmit any Viruses, or any material during the course\n    of its use of the Services that: 2.5.1 is unlawful, harmful, threatening,\
  \ defamatory, obscene, infringing, harassing\n    or racially or ethnically offensive'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/healthera/eligibility/healthera-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Healthera's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- United Kingdom
- Pharmacy
- Patient Engagement
- e-Prescribing
- NHS
- Electronic Prescription Service
- Digital Health
- Telehealth
---
