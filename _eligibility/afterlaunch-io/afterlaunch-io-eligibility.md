---
api_specs:
- filename: afterlaunch-io-api-openapi.json
  format: json
  label: AfterLaunch public API API
  slug: afterlaunch-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/afterlaunch-io/openapi/_original/afterlaunch-io-api-openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is for business use. By creating an account or subscribing you confirm that you are acting in the course of a trade, business or profession, and not as a consumer for personal, family or household purposes.
    type: business
  minimum_age:
    text: Be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: Use the Service for any illegal purpose
  - summary: Harassment or harm
    text: Use the Service to harass, defame, or harm others
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
name: AfterLaunch
provenance_date: '2026-11-09'
provider_name: AfterLaunch
provider_slug: afterlaunch-io
slug: afterlaunch-io-eligibility
source_date: '2026-11-09'
source_filename: afterlaunch-io-eligibility.yml
source_heading: Eligibility
source_page: https://afterlaunch.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AfterLaunch\naid: afterlaunch-io\nurl: https://afterlaunch.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is for business use. By creating an account or subscribing you confirm that you are acting in\n    the course of a trade, business or profession, and not as a consumer for personal, family or household purposes.\nrestricted_uses:\n- summary: Illegal purposes\n  text: Use the Service for any illegal purpose\n- summary: Harassment or harm\n  text: Use the Service to harass, defame, or harm others\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/afterlaunch-io/eligibility/afterlaunch-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AfterLaunch's own page on 2026-11-09.
synthetic: false
tags:
- SEO
- AI Search
- Growth Engine
- Site Scan
- AI Visibility
- Software-as-a-Service
- Founder Tools
---
