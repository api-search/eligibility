---
api_specs:
- filename: cefradar-com-account-api-openapi.yml
  format: yaml
  label: CEF Radar Account API
  slug: cefradar-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cefradar-com/openapi/cefradar-com-account-api-openapi.yml
- filename: cefradar-com-events-api-openapi.yml
  format: yaml
  label: CEF Radar Events API
  slug: cefradar-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cefradar-com/openapi/cefradar-com-events-api-openapi.yml
- filename: cefradar-com-funds-api-openapi.yml
  format: yaml
  label: CEF Radar Funds API
  slug: cefradar-com-funds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cefradar-com/openapi/cefradar-com-funds-api-openapi.yml
- filename: cefradar-com-investors-api-openapi.yml
  format: yaml
  label: CEF Radar Investors API
  slug: cefradar-com-investors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cefradar-com/openapi/cefradar-com-investors-api-openapi.yml
- filename: cefradar-com-search-api-openapi.yml
  format: yaml
  label: CEF Radar Search API
  slug: cefradar-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cefradar-com/openapi/cefradar-com-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old.
    value: '16'
  restricted_uses:
  - summary: Unlawful content and abuse
    text: You must not send unlawful content, try to break into the service, use another person's email address, or resell or redistribute our text.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Your account is created when you request a sign-in link and click the button on the confirmation page.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CEF Radar
provenance_date: '2026-11-09'
provider_name: CEF Radar
provider_slug: cefradar-com
slug: cefradar-com-eligibility
source_date: '2026-11-09'
source_filename: cefradar-com-eligibility.yml
source_heading: Eligibility
source_page: https://cefradar.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CEF Radar\naid: cefradar-com\nurl: https://cefradar.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful content and abuse\n  text: You must not send unlawful content, try to break into the service, use another person's email address, or\n    resell or redistribute our text.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Your account is created when you request a sign-in link and click the button on the confirmation page.\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years\
  \ old.\n"
source_yaml_url: https://artifacts.apis.io/cefradar-com/eligibility/cefradar-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from CEF Radar's own page on 2026-11-09.
synthetic: false
tags:
- Closed‑end funds
- SEC Filings
- Investor alerts
- Fund Activity
- Buybacks
---
