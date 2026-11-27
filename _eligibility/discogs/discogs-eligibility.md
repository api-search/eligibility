---
api_specs:
- filename: discogs-database-api-openapi.yml
  format: yaml
  label: Discogs Database API
  slug: discogs-database-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-database-api-openapi.yml
- filename: discogs-image-api-openapi.yml
  format: yaml
  label: Discogs Image API
  slug: discogs-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-image-api-openapi.yml
- filename: discogs-inventory-management-api-openapi.yml
  format: yaml
  label: Discogs Inventory Management API
  slug: discogs-inventory-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-inventory-management-api-openapi.yml
- filename: discogs-marketplace-api-openapi.yml
  format: yaml
  label: Discogs Marketplace API
  slug: discogs-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-marketplace-api-openapi.yml
- filename: discogs-user-collection-api-openapi.yml
  format: yaml
  label: Discogs User Collection API
  slug: discogs-user-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-user-collection-api-openapi.yml
- filename: discogs-user-identity-api-openapi.yml
  format: yaml
  label: Discogs User Identity API
  slug: discogs-user-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-user-identity-api-openapi.yml
- filename: discogs-user-lists-api-openapi.yml
  format: yaml
  label: Discogs User Lists API
  slug: discogs-user-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-user-lists-api-openapi.yml
- filename: discogs-user-wantlist-api-openapi.yml
  format: yaml
  label: Discogs User Wantlist API
  slug: discogs-user-wantlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-user-wantlist-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: In the United States, You must be at least 18 years of age to access Our API and the Content.
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: Use Our API or the Content for illegal purposes.
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
name: Discogs
provenance_date: '2026-11-09'
provider_name: Discogs
provider_slug: discogs
slug: discogs-eligibility
source_date: '2026-11-09'
source_filename: discogs-eligibility.yml
source_heading: Eligibility
source_page: https://support.discogs.com/hc/en-us/articles/360009334593-API-Terms-of-Use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Discogs\naid: discogs\nurl: https://support.discogs.com/hc/en-us/articles/360009334593-API-Terms-of-Use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal purposes\n  text: Use Our API or the Content for illegal purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In the United States, You must be at least 18 years of age to access Our API and the Content.\n"
source_yaml_url: https://artifacts.apis.io/discogs/eligibility/discogs-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Discogs's own page on 2026-11-09.
synthetic: false
tags:
- Music
- Marketplace
- Catalog
- Community
- Vinyl
- Public APIs
---
