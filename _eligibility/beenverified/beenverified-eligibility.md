---
api_specs:
- filename: beenverified-append-api-openapi.yml
  format: yaml
  label: Beenverified Append API
  slug: beenverified-append-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beenverified/openapi/beenverified-append-api-openapi.yml
- filename: beenverified-append-sandbox-api-openapi.yml
  format: yaml
  label: Beenverified Append Sandbox API
  slug: beenverified-append-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beenverified/openapi/beenverified-append-sandbox-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access the Site from, or seek information on persons residing, outside the United States.
  entity_types:
  - text: The Site and its services are available only to individuals that are at least eighteen (18) years of age and that can enter into legally binding contracts under applicable law.
    type: individual
  - text: Use the Site, Content, BeenVerified Queries or any of Our services for professional, commercial, business, governmental, collections, marketing, lead-list generating, advertising or broker/reseller services purposes
    type: business
  minimum_age:
    text: The Site and its services are available only to individuals that are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: FCRA eligibility decisions
    text: 'Because We are NOT a Consumer Reporting Agency, You are prohibited under FCRA from using any information obtained from the Site about a Search Subject including, but not limited to, information obtained through BeenVerified Queries, as a factor in determining the Search Subject’s eligibility for:'
  - summary: Fraud, harassment and harm
    text: in connection with identify theft, financial, email, or other fraud and/or in a manner that does or is intended to cause emotional or physical harm to, discriminate against, or doxing of any kind, stalking or otherwise acting to harass
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: BeenVerified will evaluate Your application and notify You of Your acceptance or rejection.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Beenverified
provenance_date: '2026-11-09'
provider_name: Beenverified
provider_slug: beenverified
slug: beenverified-eligibility
source_date: '2026-11-09'
source_filename: beenverified-eligibility.yml
source_heading: Eligibility
source_page: https://www.beenverified.com/faq/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beenverified\naid: beenverified\nurl: https://www.beenverified.com/faq/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Access the Site from, or seek information on persons residing, outside the United States.\nentity_types:\n- type: individual\n  text: The Site and its services are available only to individuals that are at least eighteen (18) years of age\n    and that can enter into legally binding contracts under applicable law.\n- type: business\n  text: Use the Site, Content, BeenVerified Queries or any of Our services for professional, commercial,\
  \ business,\n    governmental, collections, marketing, lead-list generating, advertising or broker/reseller services purposes\nrestricted_uses:\n- summary: FCRA eligibility decisions\n  text: 'Because We are NOT a Consumer Reporting Agency, You are prohibited under FCRA from using any information\n    obtained from the Site about a Search Subject including, but not limited to, information obtained through BeenVerified\n    Queries, as a factor in determining the Search Subject’s eligibility for:'\n- summary: Fraud, harassment and harm\n  text: in connection with identify theft, financial, email, or other fraud and/or in a manner that does or is intended\n    to cause emotional or physical harm to, discriminate against, or doxing of any kind, stalking or otherwise acting\n    to harass\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: BeenVerified will evaluate Your application and notify You of Your acceptance or rejection.\nminimum_age:\n  value: '18'\n  text:\
  \ The Site and its services are available only to individuals that are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/beenverified/eligibility/beenverified-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Beenverified's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Background Checks
- People Search
- Data API
- Consumer Services
---
