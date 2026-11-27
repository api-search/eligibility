---
api_specs:
- filename: twitr-sh-accounts-api-openapi.yml
  format: yaml
  label: twitr-sh Accounts API
  slug: twitr-sh-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-accounts-api-openapi.yml
- filename: twitr-sh-creator-api-openapi.yml
  format: yaml
  label: twitr-sh Creator API
  slug: twitr-sh-creator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-creator-api-openapi.yml
- filename: twitr-sh-intelligence-api-openapi.yml
  format: yaml
  label: twitr-sh Intelligence API
  slug: twitr-sh-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-intelligence-api-openapi.yml
- filename: twitr-sh-monitors-api-openapi.yml
  format: yaml
  label: twitr-sh Monitors API
  slug: twitr-sh-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-monitors-api-openapi.yml
- filename: twitr-sh-search-api-openapi.yml
  format: yaml
  label: twitr-sh Search API
  slug: twitr-sh-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-search-api-openapi.yml
- filename: twitr-sh-snapshots-api-openapi.yml
  format: yaml
  label: twitr-sh Snapshots API
  slug: twitr-sh-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-snapshots-api-openapi.yml
- filename: twitr-sh-social-api-openapi.yml
  format: yaml
  label: twitr-sh Social API
  slug: twitr-sh-social-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-social-api-openapi.yml
- filename: twitr-sh-webhooks-api-openapi.yml
  format: yaml
  label: twitr-sh Webhooks API
  slug: twitr-sh-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-webhooks-api-openapi.yml
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
  - summary: Prohibited uses
    text: 'You may not use twitr.sh for: automated mass following, unfollowing, or liking; keyword-triggered reply spam; harassment or impersonation; activity that is unlawful where you operate; or attempts to probe, overload, or interfere with the service itself.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'There is no signup: your wallet address is your account, and each request is paid individually in USDC via the x402 or MPP payment protocols.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: twitr-sh
provenance_date: '2026-11-10'
provider_name: twitr-sh
provider_slug: twitr-sh
slug: twitr-sh-eligibility
source_date: '2026-11-10'
source_filename: twitr-sh-eligibility.yml
source_heading: Eligibility
source_page: https://twitr.sh/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: twitr-sh\naid: twitr-sh\nurl: https://twitr.sh/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited uses\n  text: 'You may not use twitr.sh for: automated mass following, unfollowing, or liking; keyword-triggered reply\n    spam; harassment or impersonation; activity that is unlawful where you operate; or attempts to probe, overload,\n    or interfere with the service itself.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'There is no signup: your wallet address is your account, and each\
  \ request is paid individually in USDC\n    via the x402 or MPP payment protocols.'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/twitr-sh/eligibility/twitr-sh-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from twitr-sh's own page on 2026-11-10.
synthetic: false
tags:
- Company
- X
- Twitter
- Pay-per-call
- Artificial Intelligence
---
