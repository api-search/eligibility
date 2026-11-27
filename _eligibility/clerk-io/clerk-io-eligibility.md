---
api_specs:
- filename: clerk-io-accessories-api-openapi.yml
  format: yaml
  label: Clerk.io Accessories API
  slug: clerk-io-accessories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-accessories-api-openapi.yml
- filename: clerk-io-audiences-api-openapi.yml
  format: yaml
  label: Clerk.io Audiences API
  slug: clerk-io-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-audiences-api-openapi.yml
- filename: clerk-io-campaigns-api-openapi.yml
  format: yaml
  label: Clerk.io Campaigns API
  slug: clerk-io-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-campaigns-api-openapi.yml
- filename: clerk-io-merchandising-api-openapi.yml
  format: yaml
  label: Clerk.io Merchandising API
  slug: clerk-io-merchandising-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-merchandising-api-openapi.yml
- filename: clerk-io-privacy-api-openapi.yml
  format: yaml
  label: Clerk.io Privacy API
  slug: clerk-io-privacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-privacy-api-openapi.yml
- filename: clerk-io-recommendations-api-openapi.yml
  format: yaml
  label: Clerk.io Recommendations API
  slug: clerk-io-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-recommendations-api-openapi.yml
- filename: clerk-io-search-api-openapi.yml
  format: yaml
  label: Clerk.io Search API
  slug: clerk-io-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-search-api-openapi.yml
- filename: clerk-io-categories-api-openapi.yml
  format: yaml
  label: Clerk.io Categories API
  slug: clerk-io-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-categories-api-openapi.yml
- filename: clerk-io-customers-api-openapi.yml
  format: yaml
  label: Clerk.io Customers API
  slug: clerk-io-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-customers-api-openapi.yml
- filename: clerk-io-customized-search-api-openapi.yml
  format: yaml
  label: Clerk.io Customized Search API
  slug: clerk-io-customized-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-customized-search-api-openapi.yml
- filename: clerk-io-log-api-openapi.yml
  format: yaml
  label: Clerk.io Log API
  slug: clerk-io-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-log-api-openapi.yml
- filename: clerk-io-orders-api-openapi.yml
  format: yaml
  label: Clerk.io Orders API
  slug: clerk-io-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-orders-api-openapi.yml
- filename: clerk-io-pages-api-openapi.yml
  format: yaml
  label: Clerk.io Pages API
  slug: clerk-io-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-pages-api-openapi.yml
- filename: clerk-io-product-api-openapi.yml
  format: yaml
  label: Clerk.io Product API
  slug: clerk-io-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-product-api-openapi.yml
- filename: clerk-io-products-api-openapi.yml
  format: yaml
  label: Clerk.io Products API
  slug: clerk-io-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-products-api-openapi.yml
- filename: clerk-io-redirects-api-openapi.yml
  format: yaml
  label: Clerk.io Redirects API
  slug: clerk-io-redirects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-redirects-api-openapi.yml
- filename: clerk-io-subscriber-api-openapi.yml
  format: yaml
  label: Clerk.io Subscriber API
  slug: clerk-io-subscriber-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-subscriber-api-openapi.yml
- filename: clerk-io-synonyms-api-openapi.yml
  format: yaml
  label: Clerk.io Synonyms API
  slug: clerk-io-synonyms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-synonyms-api-openapi.yml
- filename: clerk-io-token-api-openapi.yml
  format: yaml
  label: Clerk.io Token API
  slug: clerk-io-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clerk-io/openapi/clerk-io-token-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The User must be affiliated with a business entity to use the Services.
    type: business
  - text: The Services are offered exclusively for business purposes.
    type: business
  minimum_age:
    text: The User must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No sensitive personal data
    text: The User is made aware that the Service, including the User's account, must not be used for processing of sensitive personal data as defined in GDPR article 9.
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
name: Clerk.io
provenance_date: '2026-11-09'
provider_name: Clerk.io
provider_slug: clerk-io
slug: clerk-io-eligibility
source_date: '2026-11-09'
source_filename: clerk-io-eligibility.yml
source_heading: Eligibility
source_page: https://trust.clerk.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clerk.io\naid: clerk-io\nurl: https://trust.clerk.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The User must be affiliated with a business entity to use the Services.\n- type: business\n  text: The Services are offered exclusively for business purposes.\nrestricted_uses:\n- summary: No sensitive personal data\n  text: The User is made aware that the Service, including the User's account, must not be used for processing of\n    sensitive personal data as defined in GDPR article 9.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The User must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/clerk-io/eligibility/clerk-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Clerk.io's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Commerce
- E-Commerce
- Email Marketing
- Personalization
- Recommendations
- Search
---
