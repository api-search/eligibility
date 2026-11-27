---
api_specs:
- filename: indexed-vc-companies-api-openapi.yml
  format: yaml
  label: Indexed Companies API
  slug: indexed-vc-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-companies-api-openapi.yml
- filename: indexed-vc-enrich-api-openapi.yml
  format: yaml
  label: Indexed Enrich API
  slug: indexed-vc-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-enrich-api-openapi.yml
- filename: indexed-vc-industries-api-openapi.yml
  format: yaml
  label: Indexed Industries API
  slug: indexed-vc-industries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-industries-api-openapi.yml
- filename: indexed-vc-investors-api-openapi.yml
  format: yaml
  label: Indexed Investors API
  slug: indexed-vc-investors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-investors-api-openapi.yml
- filename: indexed-vc-reveal-api-openapi.yml
  format: yaml
  label: Indexed Reveal API
  slug: indexed-vc-reveal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-reveal-api-openapi.yml
- filename: indexed-vc-scheduled-exports-api-openapi.yml
  format: yaml
  label: Indexed Scheduled Exports API
  slug: indexed-vc-scheduled-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-scheduled-exports-api-openapi.yml
- filename: indexed-vc-usage-api-openapi.yml
  format: yaml
  label: Indexed Usage API
  slug: indexed-vc-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-usage-api-openapi.yml
- filename: indexed-vc-webhooks-api-openapi.yml
  format: yaml
  label: Indexed Webhooks API
  slug: indexed-vc-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-webhooks-api-openapi.yml
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
  - summary: No unsolicited communications or spam
    text: Use the Service to send unsolicited communications, spam, or conduct any unlawful activity
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
name: Indexed
provenance_date: '2026-11-09'
provider_name: Indexed
provider_slug: indexed-vc
slug: indexed-vc-eligibility
source_date: '2026-11-09'
source_filename: indexed-vc-eligibility.yml
source_heading: Eligibility
source_page: https://indexed.vc/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Indexed\naid: indexed-vc\nurl: https://indexed.vc/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No unsolicited communications or spam\n  text: Use the Service to send unsolicited communications, spam, or conduct any unlawful activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/indexed-vc/eligibility/indexed-vc-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Indexed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Private Company
- Funding
---
