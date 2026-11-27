---
api_specs:
- filename: similarweb-account-api-openapi.yml
  format: yaml
  label: SimilarWeb Account API
  slug: similarweb-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/similarweb/openapi/similarweb-account-api-openapi.yml
- filename: similarweb-app-intelligence-api-openapi.yml
  format: yaml
  label: SimilarWeb App Intelligence API
  slug: similarweb-app-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/similarweb/openapi/similarweb-app-intelligence-api-openapi.yml
- filename: similarweb-credits-api-openapi.yml
  format: yaml
  label: SimilarWeb Credits API
  slug: similarweb-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/similarweb/openapi/similarweb-credits-api-openapi.yml
- filename: similarweb-geography-api-openapi.yml
  format: yaml
  label: SimilarWeb Geography API
  slug: similarweb-geography-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/similarweb/openapi/similarweb-geography-api-openapi.yml
- filename: similarweb-integrations-api-openapi.yml
  format: yaml
  label: SimilarWeb Integrations API
  slug: similarweb-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/similarweb/openapi/similarweb-integrations-api-openapi.yml
- filename: similarweb-keywords-api-openapi.yml
  format: yaml
  label: SimilarWeb Keywords API
  slug: similarweb-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/similarweb/openapi/similarweb-keywords-api-openapi.yml
- filename: similarweb-lead-enrichment-api-openapi.yml
  format: yaml
  label: SimilarWeb Lead Enrichment API
  slug: similarweb-lead-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/similarweb/openapi/similarweb-lead-enrichment-api-openapi.yml
- filename: similarweb-rankings-api-openapi.yml
  format: yaml
  label: SimilarWeb Rankings API
  slug: similarweb-rankings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/similarweb/openapi/similarweb-rankings-api-openapi.yml
- filename: similarweb-reports-api-openapi.yml
  format: yaml
  label: SimilarWeb Reports API
  slug: similarweb-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/similarweb/openapi/similarweb-reports-api-openapi.yml
- filename: similarweb-similar-sites-api-openapi.yml
  format: yaml
  label: SimilarWeb Similar Sites API
  slug: similarweb-similar-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/similarweb/openapi/similarweb-similar-sites-api-openapi.yml
- filename: similarweb-traffic-and-engagement-api-openapi.yml
  format: yaml
  label: SimilarWeb Traffic and Engagement API
  slug: similarweb-traffic-and-engagement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/similarweb/openapi/similarweb-traffic-and-engagement-api-openapi.yml
- filename: similarweb-traffic-sources-api-openapi.yml
  format: yaml
  label: SimilarWeb Traffic Sources API
  slug: similarweb-traffic-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/similarweb/openapi/similarweb-traffic-sources-api-openapi.yml
- filename: similarweb-webhooks-api-openapi.yml
  format: yaml
  label: SimilarWeb Webhooks API
  slug: similarweb-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/similarweb/openapi/similarweb-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you acknowledge that you, on your own behalf as an individual and/or on behalf of your employer or another legal entity
    type: individual
  - text: If you are creating an Account, you are entering into these Terms on behalf of your team, company, organization or any other entity that you either represent or belong to
    type: business
  minimum_age:
    text: you represent and warrant that you are at least 18 years old (or 13 years old if you are registering with the supervision of an adult parent or guardian).
    value: '18'
  restricted_uses:
  - summary: Competitors excluded
    text: You may not access and use the Platform if you are, and you represent and warrant that you are not, a competitor of Similarweb.
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
name: SimilarWeb
provenance_date: '2026-11-10'
provider_name: SimilarWeb
provider_slug: similarweb
slug: similarweb-eligibility
source_date: '2026-11-10'
source_filename: similarweb-eligibility.yml
source_heading: Eligibility
source_page: https://www.similarweb.com/corp/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SimilarWeb\naid: similarweb\nurl: https://www.similarweb.com/corp/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you acknowledge that you, on your own behalf as an individual and/or on behalf of your employer or another\n    legal entity\n- type: business\n  text: If you are creating an Account, you are entering into these Terms on behalf of your team, company, organization\n    or any other entity that you either represent or belong to\nrestricted_uses:\n- summary: Competitors excluded\n  text: You may not access and\
  \ use the Platform if you are, and you represent and warrant that you are not, a competitor\n    of Similarweb.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least 18 years old (or 13 years old if you are registering with\n    the supervision of an adult parent or guardian).\n"
source_yaml_url: https://artifacts.apis.io/similarweb/eligibility/similarweb-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from SimilarWeb's own page on 2026-11-10.
synthetic: false
tags:
- Digital Intelligence
- Web Analytics
- Traffic Analytics
- Competitive Intelligence
- Keyword Analytics
- Audience Demographics
- App Intelligence
- Market Research
- E-Commerce
- SEO
---
