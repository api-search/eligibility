---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Service.
    type: individual
  - text: If you are using the Service on behalf of an entity, organization, or company, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: Commercial purposes
    text: using the Service for commercial purposes, including advertising any product, service, or position, unless expressly allowed to do so by GeekWire
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
name: GeekWire
provenance_date: '2026-11-09'
provider_name: GeekWire
provider_slug: geekwire
slug: geekwire-eligibility
source_date: '2026-11-09'
source_filename: geekwire-eligibility.yml
source_heading: Eligibility
source_page: https://www.geekwire.com/termsofuse/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GeekWire\naid: geekwire\nurl: https://www.geekwire.com/termsofuse/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Service.\n- type: business\n  text: If you are using the Service on behalf of an entity, organization, or company, you represent and warrant\n    that you have the authority to bind that entity\nrestricted_uses:\n- summary: Commercial purposes\n  text: using the Service for commercial purposes, including advertising any product, service, or position, unless\n    expressly\
  \ allowed to do so by GeekWire\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/geekwire/eligibility/geekwire-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from GeekWire's own page on 2026-11-09.
synthetic: false
tags:
- Media
- Startups
- Technology News
---
