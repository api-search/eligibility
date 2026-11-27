---
api_specs:
- filename: formcarry-com-api-openapi-generated.yml
  format: yaml
  label: formcarry-com api API
  slug: api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formcarry-com/openapi/_ae-authored/formcarry-com-api-openapi-generated.yml
- filename: formcarry-com-api-reference-openapi-generated.yml
  format: yaml
  label: formcarry-com api reference API
  slug: api-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formcarry-com/openapi/_ae-authored/formcarry-com-api-reference-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under 14 years of age
    value: '14'
  restricted_uses:
  - summary: Unlawful or fraudulent purposes
    text: In any way that is unlawful or fraudulent, or has any unlawful or fraudulent purpose or effect;
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
name: formcarry-com
provenance_date: '2026-11-09'
provider_name: formcarry-com
provider_slug: formcarry-com
slug: formcarry-com-eligibility
source_date: '2026-11-09'
source_filename: formcarry-com-eligibility.yml
source_heading: Eligibility
source_page: https://formcarry.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: formcarry-com\naid: formcarry-com\nurl: https://formcarry.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or fraudulent purposes\n  text: In any way that is unlawful or fraudulent, or has any unlawful or fraudulent purpose or effect;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '14'\n  text: If you are under 14 years of age\n"
source_yaml_url: https://artifacts.apis.io/formcarry-com/eligibility/formcarry-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from formcarry-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Forms
- Backend-as-a-Service
- Webhook
---
