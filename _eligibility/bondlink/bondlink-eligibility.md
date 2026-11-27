---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: BondLink makes no representation that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: You represent you are creating this Account in your own name and not for any other individual or entity
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions compliance
    text: As a U.S. company, BondLink and its Services are subject to the U.S. economic sanctions and export control laws and regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must register for a BondLink account and you represent and warrant that all information provided to BondLink in connection with these Terms of Services, including in the process of registration for the Services, is true, accurate, and complete.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BondLink
provenance_date: '2026-11-09'
provider_name: BondLink
provider_slug: bondlink
slug: bondlink-eligibility
source_date: '2026-11-09'
source_filename: bondlink-eligibility.yml
source_heading: Eligibility
source_page: https://www.bondlink.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BondLink\naid: bondlink\nurl: https://www.bondlink.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: BondLink makes no representation that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: You represent you are creating this Account in your own name and not for any other individual or entity\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: As a U.S. company, BondLink and its Services are subject to the U.S. economic sanctions and export control\n    laws and regulations.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must register for a BondLink account and you represent and warrant that all information provided to\n    BondLink in connection with these Terms of Services, including in the process of registration for the Services,\n    is true, accurate, and complete.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bondlink/eligibility/bondlink-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from BondLink's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Software
- Municipal Bonds
- Platform
---
