---
api_specs:
- filename: unbounce-accounts-api-openapi.yml
  format: yaml
  label: Unbounce Accounts API
  slug: unbounce-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbounce/openapi/unbounce-accounts-api-openapi.yml
- filename: unbounce-domains-api-openapi.yml
  format: yaml
  label: Unbounce Domains API
  slug: unbounce-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbounce/openapi/unbounce-domains-api-openapi.yml
- filename: unbounce-leads-api-openapi.yml
  format: yaml
  label: Unbounce Leads API
  slug: unbounce-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbounce/openapi/unbounce-leads-api-openapi.yml
- filename: unbounce-meta-api-openapi.yml
  format: yaml
  label: Unbounce Meta API
  slug: unbounce-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbounce/openapi/unbounce-meta-api-openapi.yml
- filename: unbounce-pagegroups-api-openapi.yml
  format: yaml
  label: Unbounce PageGroups API
  slug: unbounce-pagegroups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbounce/openapi/unbounce-pagegroups-api-openapi.yml
- filename: unbounce-pages-api-openapi.yml
  format: yaml
  label: Unbounce Pages API
  slug: unbounce-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbounce/openapi/unbounce-pages-api-openapi.yml
- filename: unbounce-users-api-openapi.yml
  format: yaml
  label: Unbounce Users API
  slug: unbounce-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbounce/openapi/unbounce-users-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: THE SITE AND SERVICES ARE OFFERED AND CONTROLLED BY UNBOUNCE FROM ITS FACILITIES IN CANADA.
  entity_types:
  - text: if you are entering into this agreement either individually or on behalf of a company, government agency, organization, or other legal entity
    type: individual
  - text: on behalf of a company, government agency, organization, or other legal entity for whom you are an authorized representative
    type: business
  minimum_age:
    text: We will not intentionally and/or knowingly accept this Agreement from anyone under the age of sixteen (16) years, or who lacks the capacity to understand these Terms.
    value: '16'
  restricted_uses:
  - summary: Personal or sensitive information collection
    text: If you use the Services to collect, store, use, or disclose Sensitive or Personal Information about identifiable individuals, you agree only to do so in accordance with applicable law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By entering a credit card number, you agree that Unbounce, and our Third Party payment service providers, may store your payment card information for authentication, authorization and know your customer regulations.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Unbounce
provenance_date: '2026-11-10'
provider_name: Unbounce
provider_slug: unbounce
slug: unbounce-eligibility
source_date: '2026-11-10'
source_filename: unbounce-eligibility.yml
source_heading: Eligibility
source_page: https://unbounce.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unbounce\naid: unbounce\nurl: https://unbounce.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: THE SITE AND SERVICES ARE OFFERED AND CONTROLLED BY UNBOUNCE FROM ITS FACILITIES IN CANADA.\nentity_types:\n- type: individual\n  text: if you are entering into this agreement either individually or on behalf of a company, government agency,\n    organization, or other legal entity\n- type: business\n  text: on behalf of a company, government agency, organization, or other legal entity for whom you are an authorized\n    representative\nrestricted_uses:\n\
  - summary: Personal or sensitive information collection\n  text: If you use the Services to collect, store, use, or disclose Sensitive or Personal Information about identifiable\n    individuals, you agree only to do so in accordance with applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By entering a credit card number, you agree that Unbounce, and our Third Party payment service providers,\n    may store your payment card information for authentication, authorization and know your customer regulations.\nminimum_age:\n  value: '16'\n  text: We will not intentionally and/or knowingly accept this Agreement from anyone under the age of sixteen (16)\n    years, or who lacks the capacity to understand these Terms.\n"
source_yaml_url: https://artifacts.apis.io/unbounce/eligibility/unbounce-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Unbounce's own page on 2026-11-10.
synthetic: false
tags:
- Landing Pages
- Conversion Rate Optimization
- Marketing
- A/B Testing
- Lead Generation
- Marketing Automation
---
