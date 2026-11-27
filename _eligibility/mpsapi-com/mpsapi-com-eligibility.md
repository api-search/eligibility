---
api_specs:
- filename: mpsapi-com-openapi-generated.yml
  format: yaml
  label: mpsapi-com API
  slug: mpsapi-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mpsapi-com/openapi/_ae-authored/mpsapi-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old.
    type: individual
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive use
    text: Engage in any activity that violates applicable local, national, or international law;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may request verification of your identity and/or payment method where we detect indications of fraud, abuse, or disputed payments.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: mpsapi-com
provenance_date: '2026-11-10'
provider_name: mpsapi-com
provider_slug: mpsapi-com
slug: mpsapi-com-eligibility
source_date: '2026-11-10'
source_filename: mpsapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://mpsapi.com/en/terms-of-service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: mpsapi-com\naid: mpsapi-com\nurl: https://mpsapi.com/en/terms-of-service.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old.\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: Engage in any activity that violates applicable local, national, or international law;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may request verification of your identity and/or payment method where we detect indications of fraud,\n    abuse, or disputed payments.\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/mpsapi-com/eligibility/mpsapi-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from mpsapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Proxy
- Mobile
- Residential
- Reseller
---
