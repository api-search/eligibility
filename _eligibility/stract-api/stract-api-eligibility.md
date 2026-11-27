---
api_specs:
- filename: stract-api-my-user-api-openapi.yml
  format: yaml
  label: Stract API My User API
  slug: stract-api-my-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stract-api/openapi/stract-api-my-user-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Services are intended for users who are at least 18 years old.
    type: individual
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Regulated data (HIPAA, FISMA, GLBA)
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Stract API
provenance_date: '2026-11-10'
provider_name: Stract API
provider_slug: stract-api
slug: stract-api-eligibility
source_date: '2026-11-10'
source_filename: stract-api-eligibility.yml
source_heading: Eligibility
source_page: https://stract-api.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stract API\naid: stract-api\nurl: https://stract-api.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: The Services are intended for users who are at least 18 years old.\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Regulated data (HIPAA, FISMA, GLBA)\n \
  \ text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register to use the Services.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/stract-api/eligibility/stract-api-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Stract API's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Document Processing
- Data Extraction
- Software-as-a-Service
---
