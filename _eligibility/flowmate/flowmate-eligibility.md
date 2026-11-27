---
api_specs:
- filename: flowmate-openapi-generated.yml
  format: yaml
  label: FlowMate API
  slug: flowmate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowmate/openapi/_ae-authored/flowmate-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: FlowMate only offers to enter into contracts with entrepreneurs within the meaning of Section 14 of the German Civil Code (BGB), legal entities under public law, or special funds under public law. FlowMate does not enter into contracts with consumers.
    type: business
  - text: legal entities under public law, or special funds under public law
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or third-party-infringing use
    text: The customer shall not use FlowMate for unlawful purposes or in a manner that infringes the rights of third parties.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customers domiciled outside Germany but within the EU must provide their VAT identification number.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FlowMate
provenance_date: '2026-11-09'
provider_name: FlowMate
provider_slug: flowmate
slug: flowmate-eligibility
source_date: '2026-11-09'
source_filename: flowmate-eligibility.yml
source_heading: Eligibility
source_page: https://www.flowmate.io/general-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FlowMate\naid: flowmate\nurl: https://www.flowmate.io/general-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: FlowMate only offers to enter into contracts with entrepreneurs within the meaning of Section 14 of the\n    German Civil Code (BGB), legal entities under public law, or special funds under public law. FlowMate does not\n    enter into contracts with consumers.\n- type: government\n  text: legal entities under public law, or special funds under public law\nrestricted_uses:\n- summary: Unlawful or third-party-infringing\
  \ use\n  text: The customer shall not use FlowMate for unlawful purposes or in a manner that infringes the rights of third\n    parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customers domiciled outside Germany but within the EU must provide their VAT identification number.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flowmate/eligibility/flowmate-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from FlowMate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automation
- Artificial Intelligence
- Integration
- Workflows
---
