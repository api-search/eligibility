---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Services are provided from infrastructure located in Canada.
  entity_types:
  - text: you must be at least eighteen (18) years of age and have full legal capacity to enter into this contract.
    type: individual
  - text: If you are acting on behalf of a legal entity, you represent and warrant that you have the necessary authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: you must be at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Military and WMD use prohibited
    text: That it will not use the services for military purposes, nor for the design or manufacture of weapons of mass destruction;
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: BorealHost may at any time require supporting documents establishing identity, residence or beneficial ownership.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BorealHost.ai
provenance_date: '2026-11-09'
provider_name: BorealHost.ai
provider_slug: borealhost-ai
slug: borealhost-ai-eligibility
source_date: '2026-11-09'
source_filename: borealhost-ai-eligibility.yml
source_heading: Eligibility
source_page: https://borealhost.ai/en/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BorealHost.ai\naid: borealhost-ai\nurl: https://borealhost.ai/en/legal/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Services are provided from infrastructure located in Canada.\nentity_types:\n- type: individual\n  text: you must be at least eighteen (18) years of age and have full legal capacity to enter into this contract.\n- type: business\n  text: If you are acting on behalf of a legal entity, you represent and warrant that you have the necessary authority\n    to bind that entity to these Terms.\nrestricted_uses:\n- summary: Military and WMD use prohibited\n\
  \  text: That it will not use the services for military purposes, nor for the design or manufacture of weapons of\n    mass destruction;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: BorealHost may at any time require supporting documents establishing identity, residence or beneficial ownership.\nminimum_age:\n  value: '18'\n  text: you must be at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/borealhost-ai/eligibility/borealhost-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from BorealHost.ai's own page on 2026-11-09.
synthetic: false
tags:
- Hosting
- WordPress
- Quebec
- Cloud
---
