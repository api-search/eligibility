---
api_specs:
- filename: sahifa-pdf-api-openapi.yml
  format: yaml
  label: Sahifa PDF API
  slug: sahifa-pdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sahifa/openapi/sahifa-pdf-api-openapi.yml
- filename: sahifa-screenshots-api-openapi.yml
  format: yaml
  label: Sahifa Screenshots API
  slug: sahifa-screenshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sahifa/openapi/sahifa-screenshots-api-openapi.yml
- filename: sahifa-status-api-openapi.yml
  format: yaml
  label: Sahifa Status API
  slug: sahifa-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sahifa/openapi/sahifa-status-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We will not trade with or provide any services to OFAC and sanctioned countries.
  entity_types:
  - text: It is sold to businesses as a monthly subscription.
    type: business
  minimum_age:
    text: Customer using the website who are Minor / under the age of 18 shall not register as a User of the website and shall not transact on or use the website.
    value: '18'
  restricted_uses:
  - summary: Prohibited uses
    text: You may not use the service to process unlawful content, to capture or convert content you have no right to use, to attempt to reach private or internal networks, to get around the limits of a plan, or to overload third-party websites.
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
name: Sahifa
provenance_date: '2026-11-10'
provider_name: Sahifa
provider_slug: sahifa
slug: sahifa-eligibility
source_date: '2026-11-10'
source_filename: sahifa-eligibility.yml
source_heading: Eligibility
source_page: https://sahifa.dev/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sahifa\naid: sahifa\nurl: https://sahifa.dev/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We will not trade with or provide any services to OFAC and sanctioned countries.\nentity_types:\n- type: business\n  text: It is sold to businesses as a monthly subscription.\nrestricted_uses:\n- summary: Prohibited uses\n  text: You may not use the service to process unlawful content, to capture or convert content you have no right\n    to use, to attempt to reach private or internal networks, to get around the limits of a plan, or to overload\n    third-party websites.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Customer using the website who are Minor / under the age of 18 shall not register as a User of the website\n    and shall not transact on or use the website.\n"
source_yaml_url: https://artifacts.apis.io/sahifa/eligibility/sahifa-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Sahifa's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PDF
- Screenshots
- Saudi Arabia
- Cloud
---
