---
api_specs:
- filename: quiver-quantitative-beta-api-openapi.yml
  format: yaml
  label: Quiver Quantitative Beta API
  slug: quiver-quantitative-beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quiver-quantitative/openapi/quiver-quantitative-beta-api-openapi.yml
- filename: quiver-quantitative-tier-1-api-openapi.yml
  format: yaml
  label: Quiver Quantitative Tier 1 API
  slug: quiver-quantitative-tier-1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quiver-quantitative/openapi/quiver-quantitative-tier-1-api-openapi.yml
- filename: quiver-quantitative-tier-2-api-openapi.yml
  format: yaml
  label: Quiver Quantitative Tier 2 API
  slug: quiver-quantitative-tier-2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quiver-quantitative/openapi/quiver-quantitative-tier-2-api-openapi.yml
- filename: quiver-quantitative-tier-new-constructs-ratings-api-openapi.yml
  format: yaml
  label: Quiver Quantitative Tier New Constructs Ratings API
  slug: quiver-quantitative-tier-new-constructs-ratings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quiver-quantitative/openapi/quiver-quantitative-tier-new-constructs-ratings-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - GB
    text: We provide the Website and Mobile App for use only by persons located in the United States, Europe, and the United Kingdom.
  entity_types:
  - text: Our Website and Mobile App are offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: Our Website and Mobile App are offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: No commercial use of content
    text: You must not access or use for any commercial purposes any part of the Website or Mobile App or any services or materials available through the Website or Mobile App.
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
name: Quiver Quantitative
provenance_date: '2026-11-10'
provider_name: Quiver Quantitative
provider_slug: quiver-quantitative
slug: quiver-quantitative-eligibility
source_date: '2026-11-10'
source_filename: quiver-quantitative-eligibility.yml
source_heading: Eligibility
source_page: https://www.quiverquant.com/termsofservice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quiver Quantitative\naid: quiver-quantitative\nurl: https://www.quiverquant.com/termsofservice/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - GB\n  excluded: []\n  text: We provide the Website and Mobile App for use only by persons located in the United States, Europe, and\n    the United Kingdom.\nentity_types:\n- type: individual\n  text: Our Website and Mobile App are offered and available to users who are 18 years of age or older.\nrestricted_uses:\n- summary: No commercial use of content\n  text: You must not access or use for any commercial purposes any part of the Website or Mobile App\
  \ or any services\n    or materials available through the Website or Mobile App.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Website and Mobile App are offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/quiver-quantitative/eligibility/quiver-quantitative-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Quiver Quantitative's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Finance
- Politics
- Alternative Data
- Financial Data
- Investment Research
- Market Data
- Government Data
- Congressional Trading
---
