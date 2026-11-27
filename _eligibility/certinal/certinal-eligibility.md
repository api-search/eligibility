---
api_specs:
- filename: certinal-auth-api-openapi.yml
  format: yaml
  label: Certinal Auth API
  slug: certinal-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certinal/openapi/certinal-auth-api-openapi.yml
- filename: certinal-rssp-api-openapi.yml
  format: yaml
  label: Certinal Rssp API
  slug: certinal-rssp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certinal/openapi/certinal-rssp-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: CERTINAL APPLICATION IS NOT MEANT FOR MINORS UNDER THE AGE OF 18 YEARS
    value: '18'
  restricted_uses:
  - summary: Illegal or unsuitable content
    text: You are required to refrain from posting any illegal or unsuitable content.
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
name: Certinal
provenance_date: '2026-11-09'
provider_name: Certinal
provider_slug: certinal
slug: certinal-eligibility
source_date: '2026-11-09'
source_filename: certinal-eligibility.yml
source_heading: Eligibility
source_page: https://certinal.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Certinal\naid: certinal\nurl: https://certinal.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unsuitable content\n  text: You are required to refrain from posting any illegal or unsuitable content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: CERTINAL APPLICATION IS NOT MEANT FOR MINORS UNDER THE AGE OF 18 YEARS\n"
source_yaml_url: https://artifacts.apis.io/certinal/eligibility/certinal-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Certinal's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Consent
- Compliance
- E-Signature
- EHR Integration
- Regulatory
---
