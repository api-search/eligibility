---
api_specs:
- filename: alloy-cx-openapi-generated.yml
  format: yaml
  label: Alloy API
  slug: alloy-cx-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alloy-cx/openapi/_ae-authored/alloy-cx-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether personally or on behalf of an entity ("you")
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: GLBA-regulated use
    text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
  - summary: Industry-regulated interactions (HIPAA, FISMA)
    text: the Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
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
name: Alloy
provenance_date: '2026-11-09'
provider_name: Alloy
provider_slug: alloy-cx
slug: alloy-cx-eligibility
source_date: '2026-11-09'
source_filename: alloy-cx-eligibility.yml
source_heading: Eligibility
source_page: https://alloy.cx/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alloy\naid: alloy-cx\nurl: https://alloy.cx/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity (\"you\")\nrestricted_uses:\n- summary: GLBA-regulated use\n  text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\n- summary: Industry-regulated interactions (HIPAA, FISMA)\n  text: the Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information\
  \ Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/alloy-cx/eligibility/alloy-cx-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Alloy's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Artificial Intelligence
- Investment
- Automation
- CRM
---
