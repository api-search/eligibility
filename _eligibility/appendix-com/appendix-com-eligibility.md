---
api_specs:
- filename: appendix-com-api-reference-openapi-generated.yml
  format: yaml
  label: Appendix api reference API
  slug: api-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appendix-com/openapi/_ae-authored/appendix-com-api-reference-openapi-generated.yml
- filename: appendix-com-core-openapi-generated.yml
  format: yaml
  label: Appendix core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appendix-com/openapi/_ae-authored/appendix-com-core-openapi-generated.yml
- filename: appendix-com-prescribing-openapi-generated.yml
  format: yaml
  label: Appendix Prescribing API Overview API
  slug: prescribing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appendix-com/openapi/_ae-authored/appendix-com-prescribing-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Appendix Pages are offered only to users eighteen (18) years of age or older, or otherwise the age of majority in their respective jurisdictions
    type: individual
  minimum_age:
    text: The Appendix Pages are offered only to users eighteen (18) years of age or older, or otherwise the age of majority in their respective jurisdictions
    value: '18'
  restricted_uses:
  - summary: Non-emergency use only
    text: The Appendix Pages are for non-emergency use only. If you are experiencing a medical emergency, then call 911.
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
name: Appendix
provenance_date: '2026-11-09'
provider_name: Appendix
provider_slug: appendix-com
slug: appendix-com-eligibility
source_date: '2026-11-09'
source_filename: appendix-com-eligibility.yml
source_heading: Eligibility
source_page: https://appendix.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appendix\naid: appendix-com\nurl: https://appendix.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Appendix Pages are offered only to users eighteen (18) years of age or older, or otherwise the age of\n    majority in their respective jurisdictions\nrestricted_uses:\n- summary: Non-emergency use only\n  text: The Appendix Pages are for non-emergency use only. If you are experiencing a medical emergency, then call\n    911.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: The Appendix Pages are offered only to users eighteen (18) years of age or older, or otherwise the age of\n    majority in their respective jurisdictions\n"
source_yaml_url: https://artifacts.apis.io/appendix-com/eligibility/appendix-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Appendix's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Artificial Intelligence
- Telehealth
- PhysicianReview
---
