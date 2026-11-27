---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Platform is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity (“You”)
    type: individual
  - text: 'If you are using the Platform for your insurance agencies activities, You represent and warrant that: (1) You are a registered insurance agent'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Insurance agency activity requires registered agent
    text: You are a registered insurance agent and your agency license is valid when doing agency activities
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All applications are subject to underwriting approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: igloo
provenance_date: '2026-11-09'
provider_name: igloo
provider_slug: igloo
slug: igloo-eligibility
source_date: '2026-11-09'
source_filename: igloo-eligibility.yml
source_heading: Eligibility
source_page: https://contents.iglooinsure.com/termsofservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: igloo\naid: igloo\nurl: https://contents.iglooinsure.com/termsofservice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Platform is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity (“You”)\n- type: business\n  text: 'If you are using the Platform for your insurance agencies activities, You represent and warrant that: (1)\n    You are a registered\
  \ insurance agent'\nrestricted_uses:\n- summary: Insurance agency activity requires registered agent\n  text: You are a registered insurance agent and your agency license is valid when doing agency activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All applications are subject to underwriting approval.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/igloo/eligibility/igloo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from igloo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Insurance
- Insurtech
- Embedded Insurance
- Southeast Asia
- Distribution
---
