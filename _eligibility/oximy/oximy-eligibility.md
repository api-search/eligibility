---
api_specs:
- filename: oximy-init-api-openapi.yml
  format: yaml
  label: Oximy Init API
  slug: oximy-init-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oximy/openapi/oximy-init-api-openapi.yml
- filename: oximy-policy-api-openapi.yml
  format: yaml
  label: Oximy Policy API
  slug: oximy-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oximy/openapi/oximy-policy-api-openapi.yml
- filename: oximy-telemetry-api-openapi.yml
  format: yaml
  label: Oximy Telemetry API
  slug: oximy-telemetry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oximy/openapi/oximy-telemetry-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Services.
    value: '18'
  restricted_uses:
  - summary: Industry-regulated interactions
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
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
name: Oximy
provenance_date: '2026-11-10'
provider_name: Oximy
provider_slug: oximy
slug: oximy-eligibility
source_date: '2026-11-10'
source_filename: oximy-eligibility.yml
source_heading: Eligibility
source_page: https://oximy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oximy\naid: oximy\nurl: https://oximy.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: Industry-regulated interactions\n  text: The Services are not tailored\
  \ to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Services.\n"
source_yaml_url: https://artifacts.apis.io/oximy/eligibility/oximy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Oximy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Governance
- LLM Observability
- AI Adoption
- Telemetry
- Policy Enforcement
- Artificial Intelligence
- Developer Tools
---
