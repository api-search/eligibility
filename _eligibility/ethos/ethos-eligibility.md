---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The products we offer are only for people who live in the United States.
  entity_types:
  - text: you must be the person being insured on the policy
    type: individual
  minimum_age:
    text: Our Services are not available to minors.
    value: null
  restricted_uses:
  - summary: Insured must own and pay for policy
    text: you must be the person that owns and pays for the policy
  - summary: Family protection purpose required
    text: the primary purpose of the policy must be to protect your family
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
name: Ethos
provenance_date: '2026-11-09'
provider_name: Ethos
provider_slug: ethos
slug: ethos-eligibility
source_date: '2026-11-09'
source_filename: ethos-eligibility.yml
source_heading: Eligibility
source_page: https://www.ethos.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ethos\naid: ethos\nurl: https://www.ethos.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The products we offer are only for people who live in the United States.\nentity_types:\n- type: individual\n  text: you must be the person being insured on the policy\nrestricted_uses:\n- summary: Insured must own and pay for policy\n  text: you must be the person that owns and pays for the policy\n- summary: Family protection purpose required\n  text: the primary purpose of the policy must be to protect your family\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Our Services are not available to minors.\n"
source_yaml_url: https://artifacts.apis.io/ethos/eligibility/ethos-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Ethos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Life Insurance
- Insurtech
- Underwriting
- Financial Services
- Estate Planning
- Partnership API
- Fintech
- Digital
---
