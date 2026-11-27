---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are intended for adults aged 18 or older who reside in the United States.
  entity_types:
  - text: The Services are intended for adults aged 18 or older who reside in the United States.
    type: individual
  minimum_age:
    text: The Services are intended for adults aged 18 or older who reside in the United States.
    value: '18'
  restricted_uses:
  - summary: Not medical advice
    text: They do not constitute medical advice, diagnosis, or treatment
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
name: Curavit
provenance_date: '2026-11-09'
provider_name: Curavit
provider_slug: curavit
slug: curavit-eligibility
source_date: '2026-11-09'
source_filename: curavit-eligibility.yml
source_heading: Eligibility
source_page: https://curavit.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curavit\naid: curavit\nurl: https://curavit.io/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are intended for adults aged 18 or older who reside in the United States.\nentity_types:\n- type: individual\n  text: The Services are intended for adults aged 18 or older who reside in the United States.\nrestricted_uses:\n- summary: Not medical advice\n  text: They do not constitute medical advice, diagnosis, or treatment\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services\
  \ are intended for adults aged 18 or older who reside in the United States.\n"
source_yaml_url: https://artifacts.apis.io/curavit/eligibility/curavit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Curavit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CRO
- Clinical Trials
- Decentralized
- Remote
---
