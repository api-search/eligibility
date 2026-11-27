---
api_specs:
- filename: validio-openapi-generated.yml
  format: yaml
  label: Validio API
  slug: validio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validio/openapi/_ae-authored/validio-openapi-generated.yml
- filename: validio-export-api-openapi.yml
  format: yaml
  label: Validio Export API
  slug: validio-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validio/openapi/validio-export-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is intended for users who are at least 18 years old.
    type: individual
  minimum_age:
    text: The Website is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Website.
    value: '18'
  restricted_uses:
  - summary: Competing or commercial use of website
    text: Using the Website as part of any effort to compete with us or otherwise use the Website and/or the content for any revenue-generating endeavour or commercial enterprise
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
name: Validio
provenance_date: '2026-11-10'
provider_name: Validio
provider_slug: validio
slug: validio-eligibility
source_date: '2026-11-10'
source_filename: validio-eligibility.yml
source_heading: Eligibility
source_page: https://validio.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Validio\naid: validio\nurl: https://validio.io/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website is intended for users who are at least 18 years old.\nrestricted_uses:\n- summary: Competing or commercial use of website\n  text: Using the Website as part of any effort to compete with us or otherwise use the Website and/or the content\n    for any revenue-generating endeavour or commercial enterprise\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: The Website is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Website.\n"
source_yaml_url: https://artifacts.apis.io/validio/eligibility/validio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Validio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Quality
- Observability
- Data Lineage
- Artificial Intelligence
---
