---
api_specs:
- filename: ansvar-eu-openapi-generated.yml
  format: yaml
  label: ansvar-eu API
  slug: ansvar-eu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansvar-eu/openapi/_ae-authored/ansvar-eu-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is a business-to-business service provided to the Customer for use by its authorised Users. It is not offered to or intended for consumers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No special-category or criminal-offence personal data
    text: submit special-category Personal Data (Art. 9 GDPR) or personal data relating to criminal convictions and offences (Art. 10 GDPR), classified information, or export-controlled information, unless the Customer has established and can evidence a lawful basis or condition for it and Ansvar has expressly agreed in writing
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
name: ansvar-eu
provenance_date: '2026-11-09'
provider_name: ansvar-eu
provider_slug: ansvar-eu
slug: ansvar-eu-eligibility
source_date: '2026-11-09'
source_filename: ansvar-eu-eligibility.yml
source_heading: Eligibility
source_page: https://ansvar.eu/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ansvar-eu\naid: ansvar-eu\nurl: https://ansvar.eu/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is a business-to-business service provided to the Customer for use by its authorised Users.\n    It is not offered to or intended for consumers.\nrestricted_uses:\n- summary: No special-category or criminal-offence personal data\n  text: submit special-category Personal Data (Art. 9 GDPR) or personal data relating to criminal convictions and\n    offences (Art. 10 GDPR), classified information, or export-controlled information,\
  \ unless the Customer has established\n    and can evidence a lawful basis or condition for it and Ansvar has expressly agreed in writing\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ansvar-eu/eligibility/ansvar-eu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from ansvar-eu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Compliance
- Legal
- Security
- Data
---
