---
api_specs:
- filename: google-safe-browsing-hashes-api-openapi.yml
  format: yaml
  label: Google Safe Browsing Hashes API
  slug: google-safe-browsing-hashes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-safe-browsing/openapi/google-safe-browsing-hashes-api-openapi.yml
- filename: google-safe-browsing-hashlist-api-openapi.yml
  format: yaml
  label: Google Safe Browsing Hash List API
  slug: google-safe-browsing-hashlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-safe-browsing/openapi/google-safe-browsing-hashlist-api-openapi.yml
- filename: google-safe-browsing-hashlists-api-openapi.yml
  format: yaml
  label: Google Safe Browsing Hash Lists API
  slug: google-safe-browsing-hashlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-safe-browsing/openapi/google-safe-browsing-hashlists-api-openapi.yml
- filename: google-safe-browsing-projects-api-openapi.yml
  format: yaml
  label: Google Safe Browsing Projects API
  slug: google-safe-browsing-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-safe-browsing/openapi/google-safe-browsing-projects-api-openapi.yml
- filename: google-safe-browsing-threatlists-api-openapi.yml
  format: yaml
  label: Google Safe Browsing Threat Lists API
  slug: google-safe-browsing-threatlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-safe-browsing/openapi/google-safe-browsing-threatlists-api-openapi.yml
- filename: google-safe-browsing-uris-api-openapi.yml
  format: yaml
  label: Google Safe Browsing Uris API
  slug: google-safe-browsing-uris-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-safe-browsing/openapi/google-safe-browsing-uris-api-openapi.yml
- filename: google-safe-browsing-urls-api-openapi.yml
  format: yaml
  label: Google Safe Browsing URLs API
  slug: google-safe-browsing-urls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-safe-browsing/openapi/google-safe-browsing-urls-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are a business, you will defend and indemnify Google
    type: business
  minimum_age:
    text: you are not of legal age to form a binding contract with Google
    value: null
  restricted_uses:
  - summary: Life-critical uses
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
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
name: Google Safe Browsing
provenance_date: '2026-11-09'
provider_name: Google Safe Browsing
provider_slug: google-safe-browsing
slug: google-safe-browsing-eligibility
source_date: '2026-11-09'
source_filename: google-safe-browsing-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Safe Browsing\naid: google-safe-browsing\nurl: https://developers.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you are a business, you will defend and indemnify Google\nrestricted_uses:\n- summary: Life-critical uses\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not of legal age to\
  \ form a binding contract with Google\n"
source_yaml_url: https://artifacts.apis.io/google-safe-browsing/eligibility/google-safe-browsing-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Google Safe Browsing's own page on 2026-11-09.
synthetic: false
tags:
- Google
- Malware
- Safe Browsing
- Security
- Threats
- URLs
---
