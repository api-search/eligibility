---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The prices displayed are quoted in U.S. currency and are valid only in the United States.
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: if you are a child under 13 years of age, please do not attempt to register for or otherwise use the Services
    value: '13'
  restricted_uses:
  - summary: Not medical advice or emergency care
    text: Nara does not offer medical advice or diagnoses, or engage in the practice of medicine.
  - summary: Products for individual use
    text: Products are intended for individual use.
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
name: Nara Organics
provenance_date: '2026-11-10'
provider_name: Nara Organics
provider_slug: nara-organics
slug: nara-organics-eligibility
source_date: '2026-11-10'
source_filename: nara-organics-eligibility.yml
source_heading: Eligibility
source_page: https://nara.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nara Organics\naid: nara-organics\nurl: https://nara.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The prices displayed are quoted in U.S. currency and are valid only in the United States.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or\
  \ entity’s behalf\nrestricted_uses:\n- summary: Not medical advice or emergency care\n  text: Nara does not offer medical advice or diagnoses, or engage in the practice of medicine.\n- summary: Products for individual use\n  text: Products are intended for individual use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: if you are a child under 13 years of age, please do not attempt to register for or otherwise use the Services\n"
source_yaml_url: https://artifacts.apis.io/nara-organics/eligibility/nara-organics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Nara Organics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Commerce
- Retail
- Shopify
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Infant Formula
---
