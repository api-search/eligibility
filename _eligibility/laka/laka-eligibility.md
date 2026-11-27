---
api_specs:
- filename: laka-accounts-api-openapi.yml
  format: yaml
  label: Laka Accounts API
  slug: laka-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laka/openapi/laka-accounts-api-openapi.yml
- filename: laka-claims-api-openapi.yml
  format: yaml
  label: Laka Claims API
  slug: laka-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laka/openapi/laka-claims-api-openapi.yml
- filename: laka-deeplinks-api-openapi.yml
  format: yaml
  label: Laka Deeplinks API
  slug: laka-deeplinks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laka/openapi/laka-deeplinks-api-openapi.yml
- filename: laka-fleets-api-openapi.yml
  format: yaml
  label: Laka Fleets API
  slug: laka-fleets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laka/openapi/laka-fleets-api-openapi.yml
- filename: laka-policies-api-openapi.yml
  format: yaml
  label: Laka Policies API
  slug: laka-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laka/openapi/laka-policies-api-openapi.yml
- filename: laka-quote-api-openapi.yml
  format: yaml
  label: Laka Quote API
  slug: laka-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laka/openapi/laka-quote-api-openapi.yml
- filename: laka-quotes-api-openapi.yml
  format: yaml
  label: Laka Quotes API
  slug: laka-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laka/openapi/laka-quotes-api-openapi.yml
- filename: laka-reporting-api-openapi.yml
  format: yaml
  label: Laka Reporting API
  slug: laka-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laka/openapi/laka-reporting-api-openapi.yml
- filename: laka-tasks-api-openapi.yml
  format: yaml
  label: Laka Tasks API
  slug: laka-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laka/openapi/laka-tasks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing or using the Sites, you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial personal use only
    text: solely for your own personal, non-commercial use
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
name: Laka
provenance_date: '2026-11-09'
provider_name: Laka
provider_slug: laka
slug: laka-eligibility
source_date: '2026-11-09'
source_filename: laka-eligibility.yml
source_heading: Eligibility
source_page: https://laka.co/gb/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Laka\naid: laka\nurl: https://laka.co/gb/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By accessing or using the Sites, you are accepting these Terms (on behalf of yourself or the entity that\n    you represent)\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: solely for your own personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/laka/eligibility/laka-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Laka's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Cycling
- Micromobility
- Bicycle Insurance
- Claims
- Policies
- Quotes
- Embedded Insurance
- Europe
---
