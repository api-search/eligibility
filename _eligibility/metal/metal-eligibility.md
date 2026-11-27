---
api_specs:
- filename: metal-openapi-generated.yml
  format: yaml
  label: Metal API
  slug: metal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metal/openapi/_ae-authored/metal-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Website and App are controlled and operated from facilities within the U.S.; the App may not be appropriate or available in some jurisdictions.
  entity_types:
  - text: If you are entering into these Terms as an entity, then you must have the legal authority to accept these Terms on that entity's behalf
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned persons and illegal activity
    text: you will not use our Website, App, or Metropolis to conduct any illegal or illicit activity.
  - summary: VPN circumvention of restrictions
    text: You do not, and will not, use VPN software or any other privacy or anonymization tools or techniques to circumvent, or attempt to circumvent, any restrictions that apply to the Website or App.
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
name: Metal
provenance_date: '2026-11-10'
provider_name: Metal
provider_slug: metal
slug: metal-eligibility
source_date: '2026-11-10'
source_filename: metal-eligibility.yml
source_heading: Eligibility
source_page: https://metal.build/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Metal\naid: metal\nurl: https://metal.build/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Website and App are controlled and operated from facilities within the U.S.; the App may not be appropriate\n    or available in some jurisdictions.\nentity_types:\n- type: business\n  text: If you are entering into these Terms as an entity, then you must have the legal authority to accept these\n    Terms on that entity's behalf\nrestricted_uses:\n- summary: Sanctioned persons and illegal activity\n  text: you will not use our Website, App, or Metropolis to conduct any illegal or illicit\
  \ activity.\n- summary: VPN circumvention of restrictions\n  text: You do not, and will not, use VPN software or any other privacy or anonymization tools or techniques to\n    circumvent, or attempt to circumvent, any restrictions that apply to the Website or App.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/metal/eligibility/metal-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Metal's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Platform
- Cloud
- Developer Tools
- Web Applications
---
