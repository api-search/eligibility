---
api_specs:
- filename: mixrank-account-api-openapi.yml
  format: yaml
  label: MixRank Account API
  slug: mixrank-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-account-api-openapi.yml
- filename: mixrank-audience-segments-api-openapi.yml
  format: yaml
  label: MixRank Audience Segments API
  slug: mixrank-audience-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-audience-segments-api-openapi.yml
- filename: mixrank-companies-api-openapi.yml
  format: yaml
  label: MixRank Companies API
  slug: mixrank-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-companies-api-openapi.yml
- filename: mixrank-email-api-openapi.yml
  format: yaml
  label: MixRank Email API
  slug: mixrank-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-email-api-openapi.yml
- filename: mixrank-ios-app-privacy-api-openapi.yml
  format: yaml
  label: MixRank iOS App Privacy API
  slug: mixrank-ios-app-privacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-ios-app-privacy-api-openapi.yml
- filename: mixrank-ios-apps-api-openapi.yml
  format: yaml
  label: MixRank iOS Apps API
  slug: mixrank-ios-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-ios-apps-api-openapi.yml
- filename: mixrank-ios-developers-api-openapi.yml
  format: yaml
  label: MixRank iOS Developers API
  slug: mixrank-ios-developers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-ios-developers-api-openapi.yml
- filename: mixrank-ios-rankings-api-openapi.yml
  format: yaml
  label: MixRank iOS Rankings API
  slug: mixrank-ios-rankings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-ios-rankings-api-openapi.yml
- filename: mixrank-ios-sdks-api-openapi.yml
  format: yaml
  label: MixRank iOS SDKs API
  slug: mixrank-ios-sdks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-ios-sdks-api-openapi.yml
- filename: mixrank-people-api-openapi.yml
  format: yaml
  label: MixRank People API
  slug: mixrank-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-people-api-openapi.yml
- filename: mixrank-play-store-apps-api-openapi.yml
  format: yaml
  label: MixRank Play Store Apps API
  slug: mixrank-play-store-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-play-store-apps-api-openapi.yml
- filename: mixrank-play-store-developers-api-openapi.yml
  format: yaml
  label: MixRank Play Store Developers API
  slug: mixrank-play-store-developers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-play-store-developers-api-openapi.yml
- filename: mixrank-play-store-rankings-api-openapi.yml
  format: yaml
  label: MixRank Play Store Rankings API
  slug: mixrank-play-store-rankings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-play-store-rankings-api-openapi.yml
- filename: mixrank-play-store-sdks-api-openapi.yml
  format: yaml
  label: MixRank Play Store SDKs API
  slug: mixrank-play-store-sdks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-play-store-sdks-api-openapi.yml
- filename: mixrank-web-tags-api-openapi.yml
  format: yaml
  label: MixRank Web Tags API
  slug: mixrank-web-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-web-tags-api-openapi.yml
- filename: mixrank-websites-api-openapi.yml
  format: yaml
  label: MixRank Websites API
  slug: mixrank-websites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixrank/openapi/mixrank-websites-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Licensee represents that it is not a Covered Person and is not headquartered in, organized under the laws of, or owned or controlled by, a Country of Concern or Covered Person, in each case as defined under 28 C.F.R. Part 202.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: FCRA / consumer reporting
    text: (a) as or as part of a "consumer report" under the U.S. Fair Credit Reporting Act ("FCRA"), or to determine any person's eligibility for credit, insurance, employment, housing
  - summary: Political support or surveillance
    text: (c) to support or benefit a specific political candidate, party, or campaign, or for intelligence or surveillance activities, including the creation of watchlists
  - summary: Law enforcement
    text: (d) for law enforcement, criminal investigation or prosecution, or to establish evidentiary links in legal or administrative proceedings
  - summary: High-risk activities
    text: use the MixRank Platform Service with any High-Risk Activities or with activity prohibited by Applicable Laws
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
name: MixRank
provenance_date: '2026-11-10'
provider_name: MixRank
provider_slug: mixrank
slug: mixrank-eligibility
source_date: '2026-11-10'
source_filename: mixrank-eligibility.yml
source_heading: Eligibility
source_page: https://mixrank.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MixRank\naid: mixrank\nurl: https://mixrank.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Licensee represents that it is not a Covered Person and is not headquartered in, organized under the laws\n    of, or owned or controlled by, a Country of Concern or Covered Person, in each case as defined under 28 C.F.R.\n    Part 202.\nentity_types: []\nrestricted_uses:\n- summary: FCRA / consumer reporting\n  text: (a) as or as part of a \"consumer report\" under the U.S. Fair Credit Reporting Act (\"FCRA\"), or to determine\n    any person's eligibility for credit, insurance,\
  \ employment, housing\n- summary: Political support or surveillance\n  text: (c) to support or benefit a specific political candidate, party, or campaign, or for intelligence or surveillance\n    activities, including the creation of watchlists\n- summary: Law enforcement\n  text: (d) for law enforcement, criminal investigation or prosecution, or to establish evidentiary links in legal\n    or administrative proceedings\n- summary: High-risk activities\n  text: use the MixRank Platform Service with any High-Risk Activities or with activity prohibited by Applicable\n    Laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mixrank/eligibility/mixrank-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 5 quoted statements, read from MixRank's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Technographics
- Firmographics
- People Data
- Mobile App
- SDK Intelligence
- App Store
- Web Technology
- Sales Intelligence
- Data Enrichment
---
