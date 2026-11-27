---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing to these Terms on your own behalf, you represent and warrant that you are of legal age to form a binding contract.
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization or entity’s behalf
    type: business
  minimum_age:
    text: If you are agreeing to these Terms on your own behalf, you represent and warrant that you are of legal age to form a binding contract.
    value: null
  restricted_uses:
  - summary: Customer use limited to non-commercial purposes
    text: If you are a Customer, you will only use the Services for your own internal, personal, non-commercial use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: your use of the Services is also subject to a separate “Provider Agreement” that you will be required to accept prior to your use of the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LawnGuru
provenance_date: '2026-11-09'
provider_name: LawnGuru
provider_slug: lawnguru
slug: lawnguru-eligibility
source_date: '2026-11-09'
source_filename: lawnguru-eligibility.yml
source_heading: Eligibility
source_page: https://lawnguru.co/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LawnGuru\naid: lawnguru\nurl: https://lawnguru.co/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are agreeing to these Terms on your own behalf, you represent and warrant that you are of legal age\n    to form a binding contract.\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization or entity’s behalf\nrestricted_uses:\n- summary: Customer use limited to non-commercial purposes\n\
  \  text: If you are a Customer, you will only use the Services for your own internal, personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: your use of the Services is also subject to a separate “Provider Agreement” that you will be required to\n    accept prior to your use of the Services.\nminimum_age:\n  value: null\n  text: If you are agreeing to these Terms on your own behalf, you represent and warrant that you are of legal age\n    to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/lawnguru/eligibility/lawnguru-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from LawnGuru's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Lawn Care
- Home Services
- Marketplace
- On-Demand
- Landscaping
- Local Services
---
