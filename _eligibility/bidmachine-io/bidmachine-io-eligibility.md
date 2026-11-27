---
api_specs:
- filename: bidmachine-io-authentication-api-openapi.yml
  format: yaml
  label: BidMachine Authentication API
  slug: bidmachine-io-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bidmachine-io/openapi/bidmachine-io-authentication-api-openapi.yml
- filename: bidmachine-io-placements-api-openapi.yml
  format: yaml
  label: BidMachine Placements API
  slug: bidmachine-io-placements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bidmachine-io/openapi/bidmachine-io-placements-api-openapi.yml
- filename: bidmachine-io-reporting-api-openapi.yml
  format: yaml
  label: BidMachine Reporting API
  slug: bidmachine-io-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bidmachine-io/openapi/bidmachine-io-reporting-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual user, in order to utilize and register for Bidmachine Services, you must be at least 18 years old.
    type: individual
  - text: Bidmachine provides an in-app bidding solution aimed at optimizing mobile advertisements for publishers and software developers
    type: developer
  minimum_age:
    text: you must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No real-money rewards to users
    text: Under no circumstances may end users be rewarded by any “real world” monetary value unless allowed in writing by Bidmachine on a case-by-case basis
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
name: BidMachine
provenance_date: '2026-11-09'
provider_name: BidMachine
provider_slug: bidmachine-io
slug: bidmachine-io-eligibility
source_date: '2026-11-09'
source_filename: bidmachine-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.bidmachine.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BidMachine\naid: bidmachine-io\nurl: https://www.bidmachine.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual user, in order to utilize and register for Bidmachine Services, you must be at\n    least 18 years old.\n- type: developer\n  text: Bidmachine provides an in-app bidding solution aimed at optimizing mobile advertisements for publishers\n    and software developers\nrestricted_uses:\n- summary: No real-money rewards to users\n  text: Under no circumstances may end users be rewarded\
  \ by any “real world” monetary value unless allowed in writing\n    by Bidmachine on a case-by-case basis\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/bidmachine-io/eligibility/bidmachine-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BidMachine's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- AdTech
- Mobile Advertising
- Ad Exchange
- Ad Mediation
- In-App Bidding
- OpenRTB
- App Monetization
- Programmatic Advertising
- Mobile SDK
- Reporting
- Company
---
