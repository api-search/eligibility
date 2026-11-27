---
api_specs:
- filename: reputation-asset-library-api-openapi.yml
  format: yaml
  label: Reputation Asset Library API
  slug: reputation-asset-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-asset-library-api-openapi.yml
- filename: reputation-authorize-api-openapi.yml
  format: yaml
  label: Reputation Authorize API
  slug: reputation-authorize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-authorize-api-openapi.yml
- filename: reputation-categories-api-openapi.yml
  format: yaml
  label: Reputation Categories API
  slug: reputation-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-categories-api-openapi.yml
- filename: reputation-credentials-api-openapi.yml
  format: yaml
  label: Reputation Credentials API
  slug: reputation-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-credentials-api-openapi.yml
- filename: reputation-listing-audits-api-openapi.yml
  format: yaml
  label: Reputation Listing Audits API
  slug: reputation-listing-audits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-listing-audits-api-openapi.yml
- filename: reputation-locations-api-openapi.yml
  format: yaml
  label: Reputation Locations API
  slug: reputation-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-locations-api-openapi.yml
- filename: reputation-metrics-api-openapi.yml
  format: yaml
  label: Reputation Metrics API
  slug: reputation-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-metrics-api-openapi.yml
- filename: reputation-reports-api-openapi.yml
  format: yaml
  label: Reputation Reports API
  slug: reputation-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-reports-api-openapi.yml
- filename: reputation-requests-api-openapi.yml
  format: yaml
  label: Reputation Requests API
  slug: reputation-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-requests-api-openapi.yml
- filename: reputation-reviews-api-openapi.yml
  format: yaml
  label: Reputation Reviews API
  slug: reputation-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-reviews-api-openapi.yml
- filename: reputation-rich-content-api-openapi.yml
  format: yaml
  label: Reputation Rich Content API
  slug: reputation-rich-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-rich-content-api-openapi.yml
- filename: reputation-summary-api-openapi.yml
  format: yaml
  label: Reputation Summary API
  slug: reputation-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-summary-api-openapi.yml
- filename: reputation-surveys-api-openapi.yml
  format: yaml
  label: Reputation Surveys API
  slug: reputation-surveys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-surveys-api-openapi.yml
- filename: reputation-tenants-api-openapi.yml
  format: yaml
  label: Reputation Tenants API
  slug: reputation-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-tenants-api-openapi.yml
- filename: reputation-tickets-api-openapi.yml
  format: yaml
  label: Reputation Tickets API
  slug: reputation-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-tickets-api-openapi.yml
- filename: reputation-users-api-openapi.yml
  format: yaml
  label: Reputation Users API
  slug: reputation-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company or other legal entity, you also represent that you have the authority to bind such entity to these terms
    type: business
  minimum_age:
    text: you are 13 years of age or older
    value: '13'
  restricted_uses:
  - summary: Children under 13 prohibited
    text: Children under the age of 13 are prohibited from creating any accounts or purchasing or enrolling for any Services.
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
name: Reputation
provenance_date: '2026-11-10'
provider_name: Reputation
provider_slug: reputation
slug: reputation-eligibility
source_date: '2026-11-10'
source_filename: reputation-eligibility.yml
source_heading: Eligibility
source_page: https://reputation.com/legal-information/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reputation\naid: reputation\nurl: https://reputation.com/legal-information/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company or other legal entity, you also represent\n    that you have the authority to bind such entity to these terms\nrestricted_uses:\n- summary: Children under 13 prohibited\n  text: Children under the age of 13 are prohibited from creating any accounts or purchasing or enrolling for any\n    Services.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/reputation/eligibility/reputation-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Reputation's own page on 2026-11-10.
synthetic: false
tags:
- Reputation Management
- Online Reviews
- Business Listings
- Surveys
- Social Listening
- Competitive Intelligence
- Customer Experience
- Local SEO
---
