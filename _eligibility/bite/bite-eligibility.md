---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you represent and warrant that you are of legal age to form a binding contract
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: You may use the Application only for lawful purposes and in accordance with these Terms of Use.
  - summary: No sole basis for enforcement decisions
    text: Use BITE Data or Service outputs as the sole basis for legal conclusions, regulatory determinations, enforcement actions, adjudicatory decisions, or accusations against any individual or entity without independent verification;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer is required to enter into a separate agreement in order to receive white label access, authorized by company personnel with authorization levels to do so.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bite
provenance_date: '2026-11-09'
provider_name: Bite
provider_slug: bite
slug: bite-eligibility
source_date: '2026-11-09'
source_filename: bite-eligibility.yml
source_heading: Eligibility
source_page: https://bitedata.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bite\naid: bite\nurl: https://bitedata.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: You may use the Application only for lawful purposes and in accordance with these Terms of Use.\n- summary: No sole basis for enforcement decisions\n  text: Use BITE Data or Service outputs as the sole basis for legal conclusions, regulatory determinations, enforcement\n    actions, adjudicatory decisions, or accusations against any individual or entity without independent verification;\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: Customer is required to enter into a separate agreement in order to receive white label access, authorized\n    by company personnel with authorization levels to do so.\nminimum_age:\n  value: null\n  text: you represent and warrant that you are of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/bite/eligibility/bite-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Bite's own page on 2026-11-09.
synthetic: false
tags:
- Trade
- Compliance
- Artificial Intelligence
- Software-as-a-Service
- HTS
---
