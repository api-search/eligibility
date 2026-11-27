---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Export Compliance. You may not use the Service if you are located in a country or region subject to comprehensive U.S. sanctions or if you are on any U.S. government restricted-party list
  entity_types:
  - text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO ACCESS AND USE ANY PORTION OF THE SERVICE.
    type: individual
  - text: If you are agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to bind that organization or entity to these Terms
    type: business
  minimum_age:
    text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO ACCESS AND USE ANY PORTION OF THE SERVICE.
    value: '18'
  restricted_uses:
  - summary: Identifying or authenticating individuals
    text: You may not use the Service to uniquely identify, verify, or authenticate any individual
  - summary: Inferring protected-class attributes
    text: uses the Service to infer, predict, or classify the sensitive or protected-class attributes of any identifiable individual
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
name: Glyf
provenance_date: '2026-11-09'
provider_name: Glyf
provider_slug: glyf
slug: glyf-eligibility
source_date: '2026-11-09'
source_filename: glyf-eligibility.yml
source_heading: Eligibility
source_page: https://www.styleframe.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Glyf\naid: glyf\nurl: https://www.styleframe.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Export Compliance. You may not use the Service if you are located in a country or region subject to comprehensive\n    U.S. sanctions or if you are on any U.S. government restricted-party list\nentity_types:\n- type: individual\n  text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO ACCESS AND USE ANY PORTION OF THE SERVICE.\n- type: business\n  text: If you are agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are\
  \ authorized to bind that organization or entity to these Terms\nrestricted_uses:\n- summary: Identifying or authenticating individuals\n  text: You may not use the Service to uniquely identify, verify, or authenticate any individual\n- summary: Inferring protected-class attributes\n  text: uses the Service to infer, predict, or classify the sensitive or protected-class attributes of any identifiable\n    individual\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO ACCESS AND USE ANY PORTION OF THE SERVICE.\n"
source_yaml_url: https://artifacts.apis.io/glyf/eligibility/glyf-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Glyf's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Creative Tools
- Motion Graphics
- Video Generation
- Generative AI
- Design
---
