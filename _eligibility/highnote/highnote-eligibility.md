---
api_specs:
- filename: highnote-graph-ql-api-openapi.yml
  format: yaml
  label: Highnote Graph QL API
  slug: highnote-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/highnote/openapi/highnote-graph-ql-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be a commercial entity operating in the U.S..
  entity_types:
  - text: You must be a commercial entity operating in the U.S..
    type: business
  minimum_age:
    text: you must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Legitimate lawful use only
    text: You are using Highnote Platform Services and Content for legitimate purposes, are not participating in illegal or illicit activity, and are not circumventing applicable laws
  - summary: Business accounts cannot open banking
    text: A business cannot register for banking services through the Highnote Platform Services.
  verification:
    approval_required: null
    kyb: true
    kyc: null
    text: When you sign up for an account you will be required to provide us with certain information or data to create and service your account. This includes, but is not limited to your contact details and information, business activities, business details, due diligence materials, beneficial owner(s), and controller(s).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Highnote
provenance_date: '2026-11-09'
provider_name: Highnote
provider_slug: highnote
slug: highnote-eligibility
source_date: '2026-11-09'
source_filename: highnote-eligibility.yml
source_heading: Eligibility
source_page: https://highnote.com/agreements/terms/01-05-22
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Highnote\naid: highnote\nurl: https://highnote.com/agreements/terms/01-05-22\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be a commercial entity operating in the U.S..\nentity_types:\n- type: business\n  text: You must be a commercial entity operating in the U.S..\nrestricted_uses:\n- summary: Legitimate lawful use only\n  text: You are using Highnote Platform Services and Content for legitimate purposes, are not participating in illegal\n    or illicit activity, and are not circumventing applicable laws\n- summary: Business accounts cannot open banking\n  text:\
  \ A business cannot register for banking services through the Highnote Platform Services.\nverification:\n  kyc: null\n  kyb: true\n  approval_required: null\n  text: When you sign up for an account you will be required to provide us with certain information or data to create\n    and service your account. This includes, but is not limited to your contact details and information, business\n    activities, business details, due diligence materials, beneficial owner(s), and controller(s).\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/highnote/eligibility/highnote-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Highnote's own page on 2026-11-09.
synthetic: false
tags:
- Card Issuing
- Card Acquiring
- Embedded Finance
- Banking as a Service
- Fintech
- Payments
- GraphQL
- Ledger
- Credit
- Money Movement
- ACH
- KYC
- United States
---
