---
api_specs:
- filename: awin-affiliate-accounts-api-openapi.yml
  format: yaml
  label: Awin Accounts API
  slug: awin-affiliate-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awin-affiliate/openapi/awin-affiliate-accounts-api-openapi.yml
- filename: awin-affiliate-commission-groups-api-openapi.yml
  format: yaml
  label: Awin Commission Groups API
  slug: awin-affiliate-commission-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awin-affiliate/openapi/awin-affiliate-commission-groups-api-openapi.yml
- filename: awin-affiliate-programmes-api-openapi.yml
  format: yaml
  label: Awin Programmes API
  slug: awin-affiliate-programmes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awin-affiliate/openapi/awin-affiliate-programmes-api-openapi.yml
- filename: awin-affiliate-reports-api-openapi.yml
  format: yaml
  label: Awin Reports API
  slug: awin-affiliate-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awin-affiliate/openapi/awin-affiliate-reports-api-openapi.yml
- filename: awin-affiliate-transactions-api-openapi.yml
  format: yaml
  label: Awin Transactions API
  slug: awin-affiliate-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awin-affiliate/openapi/awin-affiliate-transactions-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Which terms apply depends on tax residence: "You have a tax residence in the EU and you work on programme(s) on the Awin network."'
  minimum_age:
    text: null
    value: null
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
name: Awin
provenance_date: '2026-11-09'
provider_name: Awin
provider_slug: awin-affiliate
slug: awin-affiliate-eligibility
source_date: '2026-11-09'
source_filename: awin-affiliate-eligibility.yml
source_heading: Eligibility
source_page: https://www.awin.com/gb/publisher-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Awin\naid: awin-affiliate\nurl: https://www.awin.com/gb/publisher-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Which terms apply depends on tax residence: \"You have a tax residence in the EU and you work on programme(s)\n    on the Awin network.\"'\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/awin-affiliate/eligibility/awin-affiliate-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Awin's own page on 2026-11-09.
synthetic: false
tags:
- Affiliate Marketing
- Advertising
- Publishers
- Advertisers
- Transaction
- Reporting
- Commissions
- Performance Marketing
---
