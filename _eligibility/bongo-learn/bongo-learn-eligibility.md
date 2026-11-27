---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You affirm that you are either more than 18 years of age, or an emancipated minor, or possess legal parental or guardian consent
    type: individual
  minimum_age:
    text: You affirm that you are either more than 18 years of age, or an emancipated minor, or possess legal parental or guardian consent
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access some features of the Website, you will have to create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bongo Learn
provenance_date: '2026-11-09'
provider_name: Bongo Learn
provider_slug: bongo-learn
slug: bongo-learn-eligibility
source_date: '2026-11-09'
source_filename: bongo-learn-eligibility.yml
source_heading: Eligibility
source_page: https://bongolearn.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bongo Learn\naid: bongo-learn\nurl: https://bongolearn.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You affirm that you are either more than 18 years of age, or an emancipated minor, or possess legal parental\n    or guardian consent\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to access some features of the Website, you will have to create an account.\nminimum_age:\n  value: '18'\n  text: You affirm that you are either more than 18 years of age, or an emancipated\
  \ minor, or possess legal parental\n    or guardian consent\n"
source_yaml_url: https://artifacts.apis.io/bongo-learn/eligibility/bongo-learn-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Bongo Learn's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Artificial Intelligence
- Assessment
- PartnerEnablement
- Skills Development
- Platform
---
