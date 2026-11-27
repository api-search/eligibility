---
api_specs:
- filename: ipatlas-dev-openapi-generated.yml
  format: yaml
  label: ipatlas-dev API
  slug: ipatlas-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipatlas-dev/openapi/_ae-authored/ipatlas-dev-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to create an account or use the Service.
    value: '18'
  restricted_uses:
  - summary: Free tier non-commercial only
    text: The free tier (2,000 API requests/month, or one country-level MMDB download) is licensed for non-commercial use only
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to the Service is controlled by API keys issued after card authorisation via our payment processor (Stripe).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ipatlas-dev
provenance_date: '2026-11-09'
provider_name: ipatlas-dev
provider_slug: ipatlas-dev
slug: ipatlas-dev-eligibility
source_date: '2026-11-09'
source_filename: ipatlas-dev-eligibility.yml
source_heading: Eligibility
source_page: https://ip-atlas.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ipatlas-dev\naid: ipatlas-dev\nurl: https://ip-atlas.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Free tier non-commercial only\n  text: The free tier (2,000 API requests/month, or one country-level MMDB download) is licensed for non-commercial\n    use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Access to the Service is controlled by API keys issued after card authorisation via our payment processor\n    (Stripe).\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years\
  \ old to create an account or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/ipatlas-dev/eligibility/ipatlas-dev-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from ipatlas-dev's own page on 2026-11-09.
synthetic: false
tags:
- IP
- Geolocation
- ASN
- VPN
- Data
---
