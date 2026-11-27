---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You further represent and warrant that you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a” terrorist-supporting” country
  entity_types:
  - text: If you are agreeing to be bound by these Terms on behalf of your employer or other entity, you represent and warrant that you have full legal authority to bind your employer or such entity to these Terms.
    type: business
  minimum_age:
    text: you affirm that you are at least 16 years old as the Andium Service is not intended for children under 16.
    value: '16'
  restricted_uses:
  - summary: Under-16 users
    text: If you are under 16 years of age, you are not permitted to use the Andium Service.
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
name: Andium
provenance_date: '2026-11-09'
provider_name: Andium
provider_slug: andium
slug: andium-eligibility
source_date: '2026-11-09'
source_filename: andium-eligibility.yml
source_heading: Eligibility
source_page: https://www.andium.com/andium-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Andium\naid: andium\nurl: https://www.andium.com/andium-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You further represent and warrant that you are not located in a country that is subject to a U.S. Government\n    embargo, or that has been designated by the U.S. Government as a” terrorist-supporting” country\nentity_types:\n- type: business\n  text: If you are agreeing to be bound by these Terms on behalf of your employer or other entity, you represent\n    and warrant that you have full legal authority to bind your employer or such entity to these Terms.\nrestricted_uses:\n\
  - summary: Under-16 users\n  text: If you are under 16 years of age, you are not permitted to use the Andium Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: you affirm that you are at least 16 years old as the Andium Service is not intended for children under 16.\n"
source_yaml_url: https://artifacts.apis.io/andium/eligibility/andium-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Andium's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Oil and Gas
- Industrial IoT
- Remote Monitoring
- Methane Detection
- Emissions
- Computer Vision
- Edge Computing
- Commerce
- MCP
---
