---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We control and operate the Site and our Services from Canada. We make no representation that the Site or Services are appropriate or available for use outside of Canada.
  entity_types:
  - text: The Site is available to registered and unregistered users who are 13 years old and older and who have not been suspended or removed by Blume.
    type: individual
  minimum_age:
    text: you affirm that you are over the age of 13, as the Services are not intended for persons under 13.
    value: '13'
  restricted_uses:
  - summary: Drop shipping
    text: Using the Site to drop ship merchandise to third parties.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As part of our order processing procedures, we may screen received orders for fraud or other types of unauthorized or illegal activity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Blume
provenance_date: '2026-11-09'
provider_name: Blume
provider_slug: blume
slug: blume-eligibility
source_date: '2026-11-09'
source_filename: blume-eligibility.yml
source_heading: Eligibility
source_page: https://www.blume.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blume\naid: blume\nurl: https://www.blume.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We control and operate the Site and our Services from Canada. We make no representation that the Site or\n    Services are appropriate or available for use outside of Canada.\nentity_types:\n- type: individual\n  text: The Site is available to registered and unregistered users who are 13 years old and older and who have not\n    been suspended or removed by Blume.\nrestricted_uses:\n- summary: Drop shipping\n  text: Using the Site to drop ship merchandise to third\
  \ parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As part of our order processing procedures, we may screen received orders for fraud or other types of unauthorized\n    or illegal activity.\nminimum_age:\n  value: '13'\n  text: you affirm that you are over the age of 13, as the Services are not intended for persons under 13.\n"
source_yaml_url: https://artifacts.apis.io/blume/eligibility/blume-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Blume's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Skincare
- Beauty
- Self-Care
- E-Commerce
- Consumer
- Shopify
- Agentic Commerce
- Universal Commerce Protocol
- MCP
---
