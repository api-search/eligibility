---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you qualify as a consumer under the European Union (EU), the European Economic Area (EEA), and the UK consumer regulations
  entity_types:
  - text: By accepting these Terms and using our Services you affirm you are a natural person over the age of legal majority in your country of residence
    type: individual
  minimum_age:
    text: you affirm you are a natural person over the age of legal majority in your country of residence who can enter into legally binding agreements under applicable law.
    value: legal majority
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
name: Airhelp
provenance_date: '2026-11-09'
provider_name: Airhelp
provider_slug: airhelp
slug: airhelp-eligibility
source_date: '2026-11-09'
source_filename: airhelp-eligibility.yml
source_heading: Eligibility
source_page: https://www.airhelp.com/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airhelp\naid: airhelp\nurl: https://www.airhelp.com/en/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you qualify as a consumer under the European Union (EU), the European Economic Area (EEA), and the UK\n    consumer regulations\nentity_types:\n- type: individual\n  text: By accepting these Terms and using our Services you affirm you are a natural person over the age of legal\n    majority in your country of residence\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal majority\n  text: you\
  \ affirm you are a natural person over the age of legal majority in your country of residence who can\n    enter into legally binding agreements under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/airhelp/eligibility/airhelp-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Airhelp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Flight Compensation
- Passenger Rights
- Consumer
- Legal Tech
- Insurance
---
