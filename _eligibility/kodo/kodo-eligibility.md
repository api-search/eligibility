---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - AU
    text: the Customer represents and warrants that it uses the Service only in relation to individuals located in or resident in the United States or Australia
  entity_types:
  - text: that individual also represents that the Customer is entering into the Agreement, and will use the Service, for business purposes and not for personal, family or household purposes.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive information and special categories
    text: 'The Customer must not load into a Workspace, and must not use the Service to target or message, any of the following: special category data, sensitive personal information'
  - summary: Precise geolocation of minors
    text: 'The Customer must not use the Geolocation Feature, or precise geolocation in Customer Data: (i) in relation to any individual the Customer knows, or willfully disregards, is under 18 years of age'
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
name: Kodo
provenance_date: '2026-11-09'
provider_name: Kodo
provider_slug: kodo
slug: kodo-eligibility
source_date: '2026-11-09'
source_filename: kodo-eligibility.yml
source_heading: Eligibility
source_page: https://www.kodo.co/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kodo\naid: kodo\nurl: https://www.kodo.co/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - AU\n  excluded: []\n  text: the Customer represents and warrants that it uses the Service only in relation to individuals located in\n    or resident in the United States or Australia\nentity_types:\n- type: business\n  text: that individual also represents that the Customer is entering into the Agreement, and will use the Service,\n    for business purposes and not for personal, family or household purposes.\nrestricted_uses:\n- summary: Sensitive information and special categories\n\
  \  text: 'The Customer must not load into a Workspace, and must not use the Service to target or message, any of\n    the following: special category data, sensitive personal information'\n- summary: Precise geolocation of minors\n  text: 'The Customer must not use the Geolocation Feature, or precise geolocation in Customer Data: (i) in relation\n    to any individual the Customer knows, or willfully disregards, is under 18 years of age'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kodo/eligibility/kodo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Kodo's own page on 2026-11-09.
synthetic: false
tags:
- Customer Intelligence
- Loyalty
- Rewards
- Ad Network
- Surveys
- Customer Data Platform
---
