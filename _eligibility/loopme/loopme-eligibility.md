---
api_specs:
- filename: loopme-ad-serving-api-openapi.yml
  format: yaml
  label: LoopMe S2S Ad Serving API
  slug: loopme-ad-serving-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loopme/openapi/loopme-ad-serving-api-openapi.yml
- filename: loopme-advertiser-reporting-api-openapi.yml
  format: yaml
  label: LoopMe Advertiser Reporting API
  slug: loopme-advertiser-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loopme/openapi/loopme-advertiser-reporting-api-openapi.yml
- filename: loopme-publisher-reporting-api-openapi.yml
  format: yaml
  label: LoopMe Publisher Reporting API
  slug: loopme-publisher-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loopme/openapi/loopme-publisher-reporting-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use prohibited
    text: not use the Site for any purpose that is unlawful or prohibited by these Terms.
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
name: LoopMe
provenance_date: '2026-11-09'
provider_name: LoopMe
provider_slug: loopme
slug: loopme-eligibility
source_date: '2026-11-09'
source_filename: loopme-eligibility.yml
source_heading: Eligibility
source_page: https://legal.loopme.com/legal-centre/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LoopMe\naid: loopme\nurl: https://legal.loopme.com/legal-centre/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use prohibited\n  text: not use the Site for any purpose that is unlawful or prohibited by these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/loopme/eligibility/loopme-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from LoopMe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- AdTech
- Mobile Advertising
- CTV
- Reporting
- Programmatic
- Ai Enterprise Software
- SDK
---
