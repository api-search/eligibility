---
api_specs:
- filename: immersa-openapi-generated.yml
  format: yaml
  label: Immersa API
  slug: immersa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immersa/openapi/_ae-authored/immersa-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this TOS on behalf of a Immersa, business or other legal entity, you represent that you have the authority to bind such entity and its affiliates to this TOS
    type: business
  minimum_age:
    text: you are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You may not remove or export from the United States or allow the export or re-export of the Services or anything related thereto, or any direct product thereof in violation of any restrictions, laws or regulations of the United States Department of Commerce
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
name: Immersa
provenance_date: '2026-11-09'
provider_name: Immersa
provider_slug: immersa
slug: immersa-eligibility
source_date: '2026-11-09'
source_filename: immersa-eligibility.yml
source_heading: Eligibility
source_page: https://www.marcopolo.dev/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Immersa\naid: immersa\nurl: https://www.marcopolo.dev/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this TOS on behalf of a Immersa, business or other legal entity, you represent\n    that you have the authority to bind such entity and its affiliates to this TOS\nrestricted_uses:\n- summary: Export restrictions\n  text: You may not remove or export from the United States or allow the export or re-export of the Services or\n    anything related thereto, or any direct product thereof in violation\
  \ of any restrictions, laws or regulations\n    of the United States Department of Commerce\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/immersa/eligibility/immersa-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Immersa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- DataGateway
- Platform
- Security
---
