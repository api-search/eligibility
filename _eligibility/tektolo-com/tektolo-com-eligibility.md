---
api_specs:
- filename: tektolo-com-catalog-api-openapi.yml
  format: yaml
  label: tektolo-com Catalog API
  slug: tektolo-com-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-catalog-api-openapi.yml
- filename: tektolo-com-deposit-settlement-api-openapi.yml
  format: yaml
  label: tektolo-com Deposit Settlement API
  slug: tektolo-com-deposit-settlement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-deposit-settlement-api-openapi.yml
- filename: tektolo-com-feedback-api-openapi.yml
  format: yaml
  label: tektolo-com Feedback API
  slug: tektolo-com-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-feedback-api-openapi.yml
- filename: tektolo-com-keys-api-openapi.yml
  format: yaml
  label: tektolo-com Keys API
  slug: tektolo-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-keys-api-openapi.yml
- filename: tektolo-com-property-turnover-api-openapi.yml
  format: yaml
  label: tektolo-com Property Turnover API
  slug: tektolo-com-property-turnover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-property-turnover-api-openapi.yml
- filename: tektolo-com-rules-history-api-openapi.yml
  format: yaml
  label: tektolo-com rules history API
  slug: tektolo-com-rules-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-rules-history-api-openapi.yml
- filename: tektolo-com-verify-api-openapi.yml
  format: yaml
  label: tektolo-com Verify API
  slug: tektolo-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-verify-api-openapi.yml
- filename: tektolo-com-x402-api-openapi.yml
  format: yaml
  label: tektolo-com X402 API
  slug: tektolo-com-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-x402-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18, or the age of majority where you live, and able to form a binding agreement.
    type: individual
  - text: If you use the Service for a business, you agree on its behalf.
    type: business
  minimum_age:
    text: You must be at least 18, or the age of majority where you live, and able to form a binding agreement.
    value: '18'
  restricted_uses:
  - summary: No misrepresenting outputs
    text: present outputs as a professional inspection, licensed assessment, binding quote or legal advice, or otherwise misrepresent them
  - summary: No unlawful or third-party personal data
    text: submit unlawful content, malware, or personal data of other people that you have no right to share
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: It is free to use within the published limits and needs no account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: tektolo-com
provenance_date: '2026-11-10'
provider_name: tektolo-com
provider_slug: tektolo-com
slug: tektolo-com-eligibility
source_date: '2026-11-10'
source_filename: tektolo-com-eligibility.yml
source_heading: Eligibility
source_page: https://tektolo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tektolo-com\naid: tektolo-com\nurl: https://tektolo.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18, or the age of majority where you live, and able to form a binding agreement.\n- type: business\n  text: If you use the Service for a business, you agree on its behalf.\nrestricted_uses:\n- summary: No misrepresenting outputs\n  text: present outputs as a professional inspection, licensed assessment, binding quote or legal advice, or otherwise\n    misrepresent them\n- summary: No unlawful or third-party\
  \ personal data\n  text: submit unlawful content, malware, or personal data of other people that you have no right to share\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: It is free to use within the published limits and needs no account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18, or the age of majority where you live, and able to form a binding agreement.\n"
source_yaml_url: https://artifacts.apis.io/tektolo-com/eligibility/tektolo-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from tektolo-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tools
- Artificial Intelligence
- Automation
- Reliability
---
