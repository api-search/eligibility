---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the Services are intended for use by businesses and organizations
    type: business
  - source: https://clarifyhealth.com/terms-of-use
    text: If the Customer for which You are an Authorized User is a California entity and a health care provider, You shall make sure that all Patient consents and/or authorizations required by applicable law have been obtained.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal or consumer use
    text: Use the Services for personal or consumer purposes, as the Services are intended for use by businesses and organizations;
  - summary: No harm to minors or vulnerable populations
    text: Use the Services in any manner that may harm minors or other vulnerable populations;
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
name: Clarify Health
provenance_date: '2026-11-09'
provider_name: Clarify Health
provider_slug: clarify-health
slug: clarify-health-eligibility
source_date: '2026-11-09'
source_filename: clarify-health-eligibility.yml
source_heading: Eligibility
source_page: https://clarifyhealth.com/acceptable-use-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clarify Health\naid: clarify-health\nurl: https://clarifyhealth.com/acceptable-use-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://clarifyhealth.com/acceptable-use-policy\n  - https://clarifyhealth.com/terms-of-use\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the Services are intended for use by businesses and organizations\n- type: business\n  text: If the Customer for which You are an Authorized User is a California entity and a health care provider,\n    You shall make sure that all Patient consents and/or authorizations required by applicable\
  \ law have been obtained.\n  source: https://clarifyhealth.com/terms-of-use\nrestricted_uses:\n- summary: No personal or consumer use\n  text: Use the Services for personal or consumer purposes, as the Services are intended for use by businesses and\n    organizations;\n- summary: No harm to minors or vulnerable populations\n  text: Use the Services in any manner that may harm minors or other vulnerable populations;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clarify-health/eligibility/clarify-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Clarify Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Healthcare Analytics
- Health Data
- Outcomes
- Referral Intelligence
- Payers
- Life Sciences
---
