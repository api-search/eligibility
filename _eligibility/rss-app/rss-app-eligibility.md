---
api_specs:
- filename: rss-app-bundles-api-openapi.yml
  format: yaml
  label: RSS.app Bundles API
  slug: rss-app-bundles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rss-app/openapi/rss-app-bundles-api-openapi.yml
- filename: rss-app-feed-api-openapi.yml
  format: yaml
  label: RSS.app Feed API
  slug: rss-app-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rss-app/openapi/rss-app-feed-api-openapi.yml
- filename: rss-app-rss-app-api-api-openapi.yml
  format: yaml
  label: RSS.app RSS.app API
  slug: rss-app-rss-app-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rss-app/openapi/rss-app-rss-app-api-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: No revenue-generating use of mobile app
    text: use the application for any revenue generating endeavor, commercial enterprise, or other purpose for which it is not designed or intended
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: RSS.app
provenance_date: '2026-11-10'
provider_name: RSS.app
provider_slug: rss-app
slug: rss-app-eligibility
source_date: '2026-11-10'
source_filename: rss-app-eligibility.yml
source_heading: Eligibility
source_page: https://rss.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RSS.app\naid: rss-app\nurl: https://rss.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: No revenue-generating use of mobile app\n  text: use the application for any revenue generating endeavor, commercial enterprise, or other purpose for which\n   \
  \ it is not designed or intended\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with the Site.\nminimum_age:\n  value: '13'\n  text: The Site is intended for users who are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/rss-app/eligibility/rss-app-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from RSS.app's own page on 2026-11-10.
synthetic: false
tags:
- Company
- RSS
- No-Code
- Automation
- Content
---
