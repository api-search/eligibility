---
api_specs:
- filename: refersion-affiliates-api-openapi.yml
  format: yaml
  label: Refersion Affiliates API
  slug: refersion-affiliates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refersion/openapi/refersion-affiliates-api-openapi.yml
- filename: refersion-conversions-api-openapi.yml
  format: yaml
  label: Refersion Conversions API
  slug: refersion-conversions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refersion/openapi/refersion-conversions-api-openapi.yml
- filename: refersion-offers-api-openapi.yml
  format: yaml
  label: Refersion Offers API
  slug: refersion-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refersion/openapi/refersion-offers-api-openapi.yml
- filename: refersion-reporting-api-openapi.yml
  format: yaml
  label: Refersion Reporting API
  slug: refersion-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refersion/openapi/refersion-reporting-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may only register on behalf of a corporation, the sole proprietorship of an individual 18 years or older, or another entity authorized to do business pursuant to applicable law.
    type: business
  minimum_age:
    text: the sole proprietorship of an individual 18 years or older
    value: '18'
  restricted_uses:
  - summary: Export or access in embargoed countries
    text: Customer will not permit access, use or export the Services in or to a person or country subject to a United States embargo.
  - summary: Excluded regulated data
    text: Customer represents and warrants that Customer Data does not and will not include, and Customer has not and will not process, any data through the Services that is subject to Excluded Privacy Laws
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Refersion may reject an application for an Account for any reason, in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Refersion
provenance_date: '2026-11-10'
provider_name: Refersion
provider_slug: refersion
slug: refersion-eligibility
source_date: '2026-11-10'
source_filename: refersion-eligibility.yml
source_heading: Eligibility
source_page: https://www.refersion.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Refersion\naid: refersion\nurl: https://www.refersion.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You may only register on behalf of a corporation, the sole proprietorship of an individual 18 years or older,\n    or another entity authorized to do business pursuant to applicable law.\nrestricted_uses:\n- summary: Export or access in embargoed countries\n  text: Customer will not permit access, use or export the Services in or to a person or country subject to a United\n    States embargo.\n- summary: Excluded regulated\
  \ data\n  text: Customer represents and warrants that Customer Data does not and will not include, and Customer has not\n    and will not process, any data through the Services that is subject to Excluded Privacy Laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Refersion may reject an application for an Account for any reason, in its sole discretion.\nminimum_age:\n  value: '18'\n  text: the sole proprietorship of an individual 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/refersion/eligibility/refersion-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Refersion's own page on 2026-11-10.
synthetic: false
tags:
- Affiliate Marketing
- Influencer Marketing
- E-Commerce
- Referral Tracking
- Commission Management
- Shopify
---
