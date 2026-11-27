---
api_specs:
- filename: altmetric-com-openapi-generated.yml
  format: yaml
  label: Altmetric API
  slug: altmetric-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/altmetric-com/openapi/_ae-authored/altmetric-com-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you may not use Services if not permitted by any export control or other applicable law, including because you are based in a sanctioned country or are on a sanctions list.
  entity_types:
  - text: If you agree to these terms as an individual you represent and warrant that you are at least 13 years old
    type: individual
  - text: If you agree to these terms on behalf of a business, organization, agency or institution (“an Organization”)
    type: business
  minimum_age:
    text: you represent and warrant that you are at least 13 years old and otherwise of legal age to form a binding contract
    value: '13'
  restricted_uses:
  - summary: Non-commercial internal research only
    text: The Service is provided only for your own non-commercial, internal and personal research use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Company may, in its sole discretion, refuse to offer the Service to any person or entity and change its eligibility criteria at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Altmetric
provenance_date: '2026-11-09'
provider_name: Altmetric
provider_slug: altmetric-com
slug: altmetric-com-eligibility
source_date: '2026-11-09'
source_filename: altmetric-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.altmetric.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Altmetric\naid: altmetric-com\nurl: https://www.altmetric.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you may not use Services if not permitted by any export control or other applicable law, including because\n    you are based in a sanctioned country or are on a sanctions list.\nentity_types:\n- type: individual\n  text: If you agree to these terms as an individual you represent and warrant that you are at least 13 years old\n- type: business\n  text: If you agree to these terms on behalf of a business, organization, agency or institution (“an Organization”)\n\
  restricted_uses:\n- summary: Non-commercial internal research only\n  text: The Service is provided only for your own non-commercial, internal and personal research use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Company may, in its sole discretion, refuse to offer the Service to any person or entity and change its\n    eligibility criteria at any time.\nminimum_age:\n  value: '13'\n  text: you represent and warrant that you are at least 13 years old and otherwise of legal age to form a binding\n    contract\n"
source_yaml_url: https://artifacts.apis.io/altmetric-com/eligibility/altmetric-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Altmetric's own page on 2026-11-09.
synthetic: false
tags:
- Research
- Metrics
- Analytics
- Scholarly Communication
- Altmetrics
---
