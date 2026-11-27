---
api_specs:
- filename: scento-contrast-api-openapi.yml
  format: yaml
  label: Scento Compendium API Contrast API
  slug: scento-contrast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scento/openapi/scento-contrast-api-openapi.yml
- filename: scento-perfume-portrait-api-openapi.yml
  format: yaml
  label: Scento Compendium API Perfume portrait API
  slug: scento-perfume-portrait-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scento/openapi/scento-perfume-portrait-api-openapi.yml
- filename: scento-scent-neighbours-api-openapi.yml
  format: yaml
  label: Scento Compendium API Scent neighbours API
  slug: scento-scent-neighbours-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scento/openapi/scento-scent-neighbours-api-openapi.yml
- filename: scento-search-the-compendium-api-openapi.yml
  format: yaml
  label: Scento Compendium API Search the Compendium API
  slug: scento-search-the-compendium-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scento/openapi/scento-search-the-compendium-api-openapi.yml
- filename: scento-get-a-perfume-s-notes-and-profile-api-openapi.yml
  format: yaml
  label: Scento Compendium API Get a perfume's notes and profile API
  slug: scento-get-a-perfume-s-notes-and-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scento/openapi/scento-get-a-perfume-s-notes-and-profile-api-openapi.yml
- filename: scento-search-perfumes-houses-and-notes-api-openapi.yml
  format: yaml
  label: Scento Compendium API Search perfumes, houses and notes API
  slug: scento-search-perfumes-houses-and-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scento/openapi/scento-search-perfumes-houses-and-notes-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: luxury perfume decants across Europe
  entity_types:
  - text: These Terms of Service apply to all users of the site, including without limitation users who are browsers, vendors, customers, merchants, and/ or contributors of content.
    type: business
  minimum_age:
    text: you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Orders by dealers or resellers
    text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers, resellers or distributors.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: It needs no account, no key and no payment.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Scento Compendium API
provenance_date: '2026-11-10'
provider_name: Scento Compendium API
provider_slug: scento
slug: scento-eligibility
source_date: '2026-11-10'
source_filename: scento-eligibility.yml
source_heading: Eligibility
source_page: https://www.scento.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scento Compendium API\naid: scento\nurl: https://www.scento.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: luxury perfume decants across Europe\nentity_types:\n- type: business\n  text: These Terms of Service apply to all users of the site, including without limitation users who are browsers,\n    vendors, customers, merchants, and/ or contributors of content.\nrestricted_uses:\n- summary: Orders by dealers or resellers\n  text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers,\n    resellers or distributors.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: It needs no account, no key and no payment.\nminimum_age:\n  value: age of majority\n  text: you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/scento/eligibility/scento-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Scento Compendium API's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Fragrance
- Decant
---
