---
api_specs:
- filename: commenda-openapi-generated.yml
  format: yaml
  label: Commenda API
  slug: commenda-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commenda/openapi/_ae-authored/commenda-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents ... is not ... located, organized or resident in a country or territory subject to comprehensive sanctions
  entity_types:
  - text: The individual signing an Order Form on behalf of Customer represents that he or she has the authority to bind Customer to the applicable Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions and export controls
    text: Customer will not use the Services in violation of any applicable export control or sanctions laws.
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: Customer will promptly provide such information and documentation as Company may reasonably request to comply with applicable know-your-customer, anti-money laundering and sanctions requirements.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Commenda
provenance_date: '2026-11-09'
provider_name: Commenda
provider_slug: commenda
slug: commenda-eligibility
source_date: '2026-11-09'
source_filename: commenda-eligibility.yml
source_heading: Eligibility
source_page: https://www.commenda.io/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Commenda\naid: commenda\nurl: https://www.commenda.io/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents ... is not ... located, organized or resident in a country or territory subject to comprehensive\n    sanctions\nentity_types:\n- type: business\n  text: The individual signing an Order Form on behalf of Customer represents that he or she has the authority to\n    bind Customer to the applicable Agreement.\nrestricted_uses:\n- summary: Sanctions and export controls\n  text: Customer will not use the Services in violation of any applicable\
  \ export control or sanctions laws.\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: Customer will promptly provide such information and documentation as Company may reasonably request to comply\n    with applicable know-your-customer, anti-money laundering and sanctions requirements.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/commenda/eligibility/commenda-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Commenda's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Compliance
- Global
- Tax
---
