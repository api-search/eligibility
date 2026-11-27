---
api_specs:
- filename: rsa-com-users-api-openapi.yml
  format: yaml
  label: RSA Users API
  slug: rsa-com-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rsa-com/openapi/rsa-com-users-api-openapi.yml
claim_count: 1
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
  - summary: Unlawful or prohibited use
    text: Use the Site or RSA Content for any purpose that is unlawful or prohibited by these Terms
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
name: RSA
provenance_date: '2026-11-10'
provider_name: RSA
provider_slug: rsa-com
slug: rsa-com-eligibility
source_date: '2026-11-10'
source_filename: rsa-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.rsa.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RSA\naid: rsa-com\nurl: https://www.rsa.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: Use the Site or RSA Content for any purpose that is unlawful or prohibited by these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rsa-com/eligibility/rsa-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from RSA's own page on 2026-11-10.
synthetic: false
tags:
- Identity and Access Management
- Multi-Factor Authentication
- Passwordless
- Identity Governance
- Cloud IAM
- Government
- Financial Services
---
