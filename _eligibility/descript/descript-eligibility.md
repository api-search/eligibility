---
api_specs:
- filename: descript-api-endpoints-api-openapi.yml
  format: yaml
  label: Descript API Endpoints API
  slug: descript-api-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descript/openapi/descript-api-endpoints-api-openapi.yml
- filename: descript-edit-in-descript-api-openapi.yml
  format: yaml
  label: Descript Edit in Descript API
  slug: descript-edit-in-descript-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descript/openapi/descript-edit-in-descript-api-openapi.yml
- filename: descript-export-from-descript-api-openapi.yml
  format: yaml
  label: Descript Export from Descript API
  slug: descript-export-from-descript-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descript/openapi/descript-export-from-descript-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: You must be at least 13 years of age to access or use the Descript Service.
    type: individual
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER ENTITY, YOU REPRESENT THAT YOU ARE AN EMPLOYEE OR AGENT OF SUCH COMPANY
    type: business
  minimum_age:
    text: You must be at least 13 years of age to access or use the Descript Service.
    value: '13'
  restricted_uses:
  - summary: Non-consented voice cloning
    text: attempts to clone or imitate the voice of a non-consenting speaker using our technology
  - summary: Children and protected health data content
    text: is directed to children under 16, contains any protected health information, or contains any nonpublic personal information from a financial institution
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
name: Descript
provenance_date: '2026-11-09'
provider_name: Descript
provider_slug: descript
slug: descript-eligibility
source_date: '2026-11-09'
source_filename: descript-eligibility.yml
source_heading: Eligibility
source_page: https://www.descript.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Descript\naid: descript\nurl: https://www.descript.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated\n    by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age to access or use the Descript Service.\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER ENTITY, YOU REPRESENT THAT YOU ARE\n    AN EMPLOYEE OR AGENT OF SUCH COMPANY\nrestricted_uses:\n\
  - summary: Non-consented voice cloning\n  text: attempts to clone or imitate the voice of a non-consenting speaker using our technology\n- summary: Children and protected health data content\n  text: is directed to children under 16, contains any protected health information, or contains any nonpublic personal\n    information from a financial institution\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to access or use the Descript Service.\n"
source_yaml_url: https://artifacts.apis.io/descript/eligibility/descript-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Descript's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Audio Editing
- Captions
- Media
- Podcasts
- Transcription
- Video Editing
- Audio
---
