---
api_specs:
- filename: chateaupedia-com-openapi-generated.yml
  format: yaml
  label: Chateaupedia API
  slug: chateaupedia-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chateaupedia-com/openapi/_ae-authored/chateaupedia-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The site addresses a European audience and processes data of European Union residents.
  entity_types:
  - text: a business customer has no fourteen-day right of withdrawal
    type: business
  - text: it does apply to anyone acting for non-professional purposes
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: API key revocation
    text: we reserve the right to revoke a key that degrades the service for others.
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
name: Chateaupedia
provenance_date: '2026-11-09'
provider_name: Chateaupedia
provider_slug: chateaupedia-com
slug: chateaupedia-com-eligibility
source_date: '2026-11-09'
source_filename: chateaupedia-com-eligibility.yml
source_heading: Eligibility
source_page: https://chateaupedia.com/en/cgv
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chateaupedia\naid: chateaupedia-com\nurl: https://chateaupedia.com/en/cgv\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The site addresses a European audience and processes data of European Union residents.\nentity_types:\n- type: business\n  text: a business customer has no fourteen-day right of withdrawal\n- type: individual\n  text: it does apply to anyone acting for non-professional purposes\nrestricted_uses:\n- summary: API key revocation\n  text: we reserve the right to revoke a key that degrades the service for others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chateaupedia-com/eligibility/chateaupedia-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Chateaupedia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Castles
- Tourism
- Travel
- Cultural Heritage
- Open Data
- Directory
- France
- Germany
---
