---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no claims that the Website or any of its content is accessible or appropriate outside of the United States.
  entity_types:
  - text: The Website is offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: The Website is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Not medical advice
    text: The information provided on this website is for general informational purposes only and is not intended as medical advice, diagnosis, or treatment.
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
name: Celcuity
provenance_date: '2026-11-09'
provider_name: Celcuity
provider_slug: celcuity
slug: celcuity-eligibility
source_date: '2026-11-09'
source_filename: celcuity-eligibility.yml
source_heading: Eligibility
source_page: https://www.celcuity.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Celcuity\naid: celcuity\nurl: https://www.celcuity.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no claims that the Website or any of its content is accessible or appropriate outside of the United\n    States.\nentity_types:\n- type: individual\n  text: The Website is offered and available to users who are 18 years of age or older.\nrestricted_uses:\n- summary: Not medical advice\n  text: The information provided on this website is for general informational purposes only and is not intended\n    as medical advice, diagnosis, or treatment.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/celcuity/eligibility/celcuity-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Celcuity's own page on 2026-11-09.
synthetic: false
tags:
- Cancer therapies
- Clinical Trials
- Breast Cancer
- Prostate Cancer
- Solid tumors
---
