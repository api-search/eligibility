---
api_specs:
- filename: adslighthouse-account-api-openapi.yml
  format: yaml
  label: Ads Lighthouse Account API
  slug: adslighthouse-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adslighthouse/openapi/adslighthouse-account-api-openapi.yml
- filename: adslighthouse-alerts-api-openapi.yml
  format: yaml
  label: Ads Lighthouse Alerts API
  slug: adslighthouse-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adslighthouse/openapi/adslighthouse-alerts-api-openapi.yml
- filename: adslighthouse-checks-api-openapi.yml
  format: yaml
  label: Ads Lighthouse Checks API
  slug: adslighthouse-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adslighthouse/openapi/adslighthouse-checks-api-openapi.yml
- filename: adslighthouse-google-api-openapi.yml
  format: yaml
  label: Ads Lighthouse Google API
  slug: adslighthouse-google-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adslighthouse/openapi/adslighthouse-google-api-openapi.yml
- filename: adslighthouse-keywords-api-openapi.yml
  format: yaml
  label: Ads Lighthouse Keywords API
  slug: adslighthouse-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adslighthouse/openapi/adslighthouse-keywords-api-openapi.yml
- filename: adslighthouse-matching-api-openapi.yml
  format: yaml
  label: Ads Lighthouse Matching API
  slug: adslighthouse-matching-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adslighthouse/openapi/adslighthouse-matching-api-openapi.yml
- filename: adslighthouse-observations-api-openapi.yml
  format: yaml
  label: Ads Lighthouse Observations API
  slug: adslighthouse-observations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adslighthouse/openapi/adslighthouse-observations-api-openapi.yml
- filename: adslighthouse-policy-api-openapi.yml
  format: yaml
  label: Ads Lighthouse Policy API
  slug: adslighthouse-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adslighthouse/openapi/adslighthouse-policy-api-openapi.yml
- filename: adslighthouse-prices-api-openapi.yml
  format: yaml
  label: Ads Lighthouse Prices API
  slug: adslighthouse-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adslighthouse/openapi/adslighthouse-prices-api-openapi.yml
- filename: adslighthouse-projects-api-openapi.yml
  format: yaml
  label: Ads Lighthouse Projects API
  slug: adslighthouse-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adslighthouse/openapi/adslighthouse-projects-api-openapi.yml
- filename: adslighthouse-redirect-chains-api-openapi.yml
  format: yaml
  label: Ads Lighthouse Redirect chains API
  slug: adslighthouse-redirect-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adslighthouse/openapi/adslighthouse-redirect-chains-api-openapi.yml
- filename: adslighthouse-reports-api-openapi.yml
  format: yaml
  label: Ads Lighthouse Reports API
  slug: adslighthouse-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adslighthouse/openapi/adslighthouse-reports-api-openapi.yml
- filename: adslighthouse-router-api-openapi.yml
  format: yaml
  label: Ads Lighthouse Router API
  slug: adslighthouse-router-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adslighthouse/openapi/adslighthouse-router-api-openapi.yml
- filename: adslighthouse-team-api-openapi.yml
  format: yaml
  label: Ads Lighthouse Team API
  slug: adslighthouse-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adslighthouse/openapi/adslighthouse-team-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Ads Lighthouse is intended for business customers who use it for their trade, business or profession. It is not offered to consumers.
    type: business
  minimum_age:
    text: You must be an adult with authority to act for the business whose account you use.
    value: adult
  restricted_uses:
  - summary: Harassment or misrepresentation
    text: Do not use monitoring to harass people, misrepresent an advertiser's conduct or publish allegations without appropriate review.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: When you create an account or subscribe, you confirm that you act for a business.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ads Lighthouse
provenance_date: '2026-11-09'
provider_name: Ads Lighthouse
provider_slug: adslighthouse
slug: adslighthouse-eligibility
source_date: '2026-11-09'
source_filename: adslighthouse-eligibility.yml
source_heading: Eligibility
source_page: https://adslighthouse.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ads Lighthouse\naid: adslighthouse\nurl: https://adslighthouse.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Ads Lighthouse is intended for business customers who use it for their trade, business or profession. It\n    is not offered to consumers.\nrestricted_uses:\n- summary: Harassment or misrepresentation\n  text: Do not use monitoring to harass people, misrepresent an advertiser's conduct or publish allegations without\n    appropriate review.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: When you create an account or subscribe, you confirm that you act for a business.\nminimum_age:\n  value: adult\n  text: You must be an adult with authority to act for the business whose account you use.\n"
source_yaml_url: https://artifacts.apis.io/adslighthouse/eligibility/adslighthouse-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Ads Lighthouse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- Monitoring
- Brand Protection
---
