---
api_specs:
- filename: tatango-openapi-generated.yml
  format: yaml
  label: Tatango API
  slug: tatango-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tatango/openapi/_ae-authored/tatango-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “You” and “Customer” refers to the entity or organization using the Platform and/or Services described in this MSA.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: TCPA compliance required
    text: (g) comply with the Telephone Consumer Protection Act (“ TCPA ”), 47 U.S.C. § 227 et seq.
  - summary: No sensitive health, financial or ID numbers
    text: (c) it will not upload to or send through the Platform any social security numbers, passport numbers, financial account numbers, credit card information
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
name: Tatango
provenance_date: '2026-11-10'
provider_name: Tatango
provider_slug: tatango
slug: tatango-eligibility
source_date: '2026-11-10'
source_filename: tatango-eligibility.yml
source_heading: Eligibility
source_page: https://www.tatango.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tatango\naid: tatango\nurl: https://www.tatango.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “You” and “Customer” refers to the entity or organization using the Platform and/or Services described in\n    this MSA.\nrestricted_uses:\n- summary: TCPA compliance required\n  text: (g) comply with the Telephone Consumer Protection Act (“ TCPA ”), 47 U.S.C. § 227 et seq.\n- summary: No sensitive health, financial or ID numbers\n  text: (c) it will not upload to or send through the Platform any social security numbers,\
  \ passport numbers, financial\n    account numbers, credit card information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tatango/eligibility/tatango-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Tatango's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SMS
- Fundraising
- Non-Profit
- Marketing
---
