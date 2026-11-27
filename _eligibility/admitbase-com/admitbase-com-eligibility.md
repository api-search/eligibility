---
api_specs:
- filename: admitbase-com-openapi-generated.yml
  format: yaml
  label: AdmitBase API
  slug: admitbase-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/admitbase-com/openapi/_ae-authored/admitbase-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: Use the Service for any unlawful purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use certain features, you must create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AdmitBase
provenance_date: '2026-11-09'
provider_name: AdmitBase
provider_slug: admitbase-com
slug: admitbase-com-eligibility
source_date: '2026-11-09'
source_filename: admitbase-com-eligibility.yml
source_heading: Eligibility
source_page: https://admitbase.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdmitBase\naid: admitbase-com\nurl: https://admitbase.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use the Service for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use certain features, you must create an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/admitbase-com/eligibility/admitbase-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from AdmitBase's own page on 2026-11-09.
synthetic: false
tags:
- Admissions
- Law
- Medical
- Dental
- Education
---
