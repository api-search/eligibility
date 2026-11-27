---
api_specs:
- filename: jsonpad-io-openapi-generated.yml
  format: yaml
  label: jsonpad-io API
  slug: jsonpad-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jsonpad-io/openapi/_ae-authored/jsonpad-io-openapi-generated.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity ("you")
    type: individual
  - text: whether personally or on behalf of an entity ("you")
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Industry-specific regulated data (HIPAA, FISMA)
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  - summary: GLBA-violating use
    text: You may not use the Services in a way that would violate the Gramm-Leach-BlileyAct (GLBA).
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
name: jsonpad-io
provenance_date: '2026-11-09'
provider_name: jsonpad-io
provider_slug: jsonpad-io
slug: jsonpad-io-eligibility
source_date: '2026-11-09'
source_filename: jsonpad-io-eligibility.yml
source_heading: Eligibility
source_page: https://jsonpad.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: jsonpad-io\naid: jsonpad-io\nurl: https://jsonpad.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity (\"you\")\n- type: business\n  text: whether personally or on behalf of an entity (\"you\")\nrestricted_uses:\n- summary: Industry-specific regulated data (HIPAA, FISMA)\n\
  \  text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\n- summary: GLBA-violating use\n  text: You may not use the Services in a way that would violate the Gramm-Leach-BlileyAct (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register to use the Services.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/jsonpad-io/eligibility/jsonpad-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from jsonpad-io's own page on 2026-11-09.
synthetic: false
tags:
- JSON Storage
- REST API
- No-Code Backend
- Real-time Updates
- Versioning
---
