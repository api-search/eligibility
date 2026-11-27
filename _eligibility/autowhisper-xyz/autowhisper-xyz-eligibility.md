---
api_specs:
- filename: autowhisper-xyz-openapi-generated.yml
  format: yaml
  label: AutoWhisper API
  slug: autowhisper-xyz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autowhisper-xyz/openapi/_ae-authored/autowhisper-xyz-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be at least 18 years old and have full legal capacity, or have obtained consent from your legal guardian
    type: individual
  - text: If you accept these Terms on behalf of a business or organization, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: Be at least 18 years old and have full legal capacity, or have obtained consent from your legal guardian
    value: '18'
  restricted_uses:
  - summary: Prohibited conduct and content
    text: You expressly agree not to engage in any of the following conduct, violation of which will result in immediate suspension or termination of your account
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
name: AutoWhisper
provenance_date: '2026-11-09'
provider_name: AutoWhisper
provider_slug: autowhisper-xyz
slug: autowhisper-xyz-eligibility
source_date: '2026-11-09'
source_filename: autowhisper-xyz-eligibility.yml
source_heading: Eligibility
source_page: https://autowhisper.xyz/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AutoWhisper\naid: autowhisper-xyz\nurl: https://autowhisper.xyz/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be at least 18 years old and have full legal capacity, or have obtained consent from your legal guardian\n- type: business\n  text: If you accept these Terms on behalf of a business or organization, you represent and warrant that you have\n    the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Prohibited conduct and content\n  text: You expressly agree not to engage in any of the following\
  \ conduct, violation of which will result in immediate\n    suspension or termination of your account\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old and have full legal capacity, or have obtained consent from your legal guardian\n"
source_yaml_url: https://artifacts.apis.io/autowhisper-xyz/eligibility/autowhisper-xyz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AutoWhisper's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- E-Commerce
- Content Generation
- Automation
---
