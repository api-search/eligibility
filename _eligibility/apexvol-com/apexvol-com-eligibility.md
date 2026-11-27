---
api_specs:
- filename: apexvol-com-account-and-index-api-openapi.yml
  format: yaml
  label: ApexVol Account and index API
  slug: apexvol-com-account-and-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-account-and-index-api-openapi.yml
- filename: apexvol-com-earnings-and-expected-move-api-openapi.yml
  format: yaml
  label: ApexVol Earnings and expected move API
  slug: apexvol-com-earnings-and-expected-move-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-earnings-and-expected-move-api-openapi.yml
- filename: apexvol-com-events-and-calendars-api-openapi.yml
  format: yaml
  label: ApexVol Events and calendars API
  slug: apexvol-com-events-and-calendars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-events-and-calendars-api-openapi.yml
- filename: apexvol-com-gamma-exposure-api-openapi.yml
  format: yaml
  label: ApexVol Gamma exposure API
  slug: apexvol-com-gamma-exposure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-gamma-exposure-api-openapi.yml
- filename: apexvol-com-implied-volatility-api-openapi.yml
  format: yaml
  label: ApexVol Implied volatility API
  slug: apexvol-com-implied-volatility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-implied-volatility-api-openapi.yml
- filename: apexvol-com-options-chain-api-openapi.yml
  format: yaml
  label: ApexVol Options chain API
  slug: apexvol-com-options-chain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-options-chain-api-openapi.yml
- filename: apexvol-com-options-flow-api-openapi.yml
  format: yaml
  label: ApexVol Options flow API
  slug: apexvol-com-options-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-options-flow-api-openapi.yml
- filename: apexvol-com-options-greeks-api-openapi.yml
  format: yaml
  label: ApexVol Options Greeks API
  slug: apexvol-com-options-greeks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-options-greeks-api-openapi.yml
- filename: apexvol-com-portfolio-risk-api-openapi.yml
  format: yaml
  label: ApexVol Portfolio risk API
  slug: apexvol-com-portfolio-risk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-portfolio-risk-api-openapi.yml
- filename: apexvol-com-screeners-api-openapi.yml
  format: yaml
  label: ApexVol Screeners API
  slug: apexvol-com-screeners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-screeners-api-openapi.yml
- filename: apexvol-com-stock-analytics-api-openapi.yml
  format: yaml
  label: ApexVol Stock analytics API
  slug: apexvol-com-stock-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-stock-analytics-api-openapi.yml
- filename: apexvol-com-strategies-api-openapi.yml
  format: yaml
  label: ApexVol Strategies API
  slug: apexvol-com-strategies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-strategies-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you (i) are not located in, under the control of, or a national or resident of any country subject to U.K., E.U., U.S., or U.N. trade sanctions or embargoes
  entity_types:
  - text: You must be at least 18 years old (or the age of majority where you reside, if greater) and have the legal capacity to enter into a contract to use the Services.
    type: individual
  - text: If you are acting in the course of a business (and not as a Consumer), you agree to defend, indemnify, and hold harmless ApexVol
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority where you reside, if greater)
    value: '18'
  restricted_uses:
  - summary: Sanctioned jurisdictions or parties
    text: are not a prohibited party under applicable export or sanctions laws
  - summary: Insider trading and market manipulation
    text: engage in or facilitate insider trading, market manipulation, money laundering, or other illicit or unethical activities
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: ApexVol reserves the right to refuse registration, suspend, or terminate any Account at its discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ApexVol
provenance_date: '2026-11-09'
provider_name: ApexVol
provider_slug: apexvol-com
slug: apexvol-com-eligibility
source_date: '2026-11-09'
source_filename: apexvol-com-eligibility.yml
source_heading: Eligibility
source_page: https://apexvol.com/terms_and_conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ApexVol\naid: apexvol-com\nurl: https://apexvol.com/terms_and_conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you (i) are not located in, under the control of, or a national or resident\n    of any country subject to U.K., E.U., U.S., or U.N. trade sanctions or embargoes\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority where you reside, if greater) and have the legal\n    capacity to enter into a contract to use the Services.\n- type: business\n  text: If you are acting in the course of\
  \ a business (and not as a Consumer), you agree to defend, indemnify, and\n    hold harmless ApexVol\nrestricted_uses:\n- summary: Sanctioned jurisdictions or parties\n  text: are not a prohibited party under applicable export or sanctions laws\n- summary: Insider trading and market manipulation\n  text: engage in or facilitate insider trading, market manipulation, money laundering, or other illicit or unethical\n    activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: ApexVol reserves the right to refuse registration, suspend, or terminate any Account at its discretion.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority where you reside, if greater)\n"
source_yaml_url: https://artifacts.apis.io/apexvol-com/eligibility/apexvol-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from ApexVol's own page on 2026-11-09.
synthetic: false
tags:
- Options
- Analytics
- Trading
- Finance
- Terminal
---
