---
api_specs:
- filename: rhizome-ai-documents-api-openapi.yml
  format: yaml
  label: Rhizome Ai Documents API
  slug: rhizome-ai-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhizome-ai/openapi/rhizome-ai-documents-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Services.
    type: individual
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No patient-level or health special-category data
    text: The Services are intended for research against published regulatory and scientific material and are not designed to receive, store, or process such data.
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
name: Rhizome Ai
provenance_date: '2026-11-10'
provider_name: Rhizome Ai
provider_slug: rhizome-ai
slug: rhizome-ai-eligibility
source_date: '2026-11-10'
source_filename: rhizome-ai-eligibility.yml
source_heading: Eligibility
source_page: https://rhizomeai.com/termsofservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rhizome Ai\naid: rhizome-ai\nurl: https://rhizomeai.com/termsofservice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Services.\n- type: business\n  text: These Legal Terms constitute\
  \ a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: No patient-level or health special-category data\n  text: The Services are intended for research against published regulatory and scientific material and are not\n    designed to receive, store, or process such data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/rhizome-ai/eligibility/rhizome-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Rhizome Ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Regulatory
- Pharmaceuticals
- Medical Devices
- Life Sciences
- Document Search
- Artificial Intelligence
- Compliance
---
