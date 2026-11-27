---
api_specs:
- filename: halliday-assets-api-openapi.yml
  format: yaml
  label: Halliday Assets API
  slug: halliday-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halliday/openapi/halliday-assets-api-openapi.yml
- filename: halliday-chains-api-openapi.yml
  format: yaml
  label: Halliday Chains API
  slug: halliday-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halliday/openapi/halliday-chains-api-openapi.yml
- filename: halliday-payments-api-openapi.yml
  format: yaml
  label: Halliday Payments API
  slug: halliday-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halliday/openapi/halliday-payments-api-openapi.yml
- filename: halliday-webhooks-api-openapi.yml
  format: yaml
  label: Halliday Webhooks API
  slug: halliday-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halliday/openapi/halliday-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Prohibited Persons include those located or organized in U.S. embargoed countries or any country designated by the U.S. Government as “terrorist supporting”, without naming them.
  minimum_age:
    text: You must be at least 18 years of age or older and not be a Prohibited Person to use the Features. Children under the age of 18 are not permitted to use the Features.
    value: '18'
  restricted_uses:
  - summary: Illegal or prohibited activity
    text: will not be using the Features for any illegal activity or to engage in any prohibited activities provided herein
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
name: Halliday
provenance_date: '2026-11-09'
provider_name: Halliday
provider_slug: halliday
slug: halliday-eligibility
source_date: '2026-11-09'
source_filename: halliday-eligibility.yml
source_heading: Eligibility
source_page: https://www.halliday.xyz/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Halliday\naid: halliday\nurl: https://www.halliday.xyz/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Prohibited Persons include those located or organized in U.S. embargoed countries or any country designated\n    by the U.S. Government as “terrorist supporting”, without naming them.\nentity_types: []\nrestricted_uses:\n- summary: Illegal or prohibited activity\n  text: will not be using the Features for any illegal activity or to engage in any prohibited activities provided\n    herein\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age or older and not be a Prohibited Person to use the Features. Children\n    under the age of 18 are not permitted to use the Features.\n"
source_yaml_url: https://artifacts.apis.io/halliday/eligibility/halliday-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Halliday's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Cryptocurrency
- Blockchain
- Web3
- On-Ramp
- Swap
- DeFi
- Agentic Workflows
- Fintech
---
