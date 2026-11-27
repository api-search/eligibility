---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The License is described as a worldwide license to access and use the products and services.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not investment advice
    text: the information provided through the products is for informational purposes only and should not be construed as financial, legal, investment or other advice or recommendations of any kind.
  - summary: Not basis for securities transactions
    text: KAYRROS REPORTS DO NOT CONTAIN ANY RECOMMENDATIONS TO BUY OR SELL ANY SECURITIES OR COMMODITY INTERESTS AND SHOULD NOT BE RELIED UPON AS THE BASIS FOR ANY TRANSACTIONS IN SECURITIES OR COMMODITY INTERESTS.
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
name: Kayrros
provenance_date: '2026-11-09'
provider_name: Kayrros
provider_slug: kayrros
slug: kayrros-eligibility
source_date: '2026-11-09'
source_filename: kayrros-eligibility.yml
source_heading: Eligibility
source_page: https://www.kayrros.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kayrros\naid: kayrros\nurl: https://www.kayrros.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The License is described as a worldwide license to access and use the products and services.\nentity_types: []\nrestricted_uses:\n- summary: Not investment advice\n  text: the information provided through the products is for informational purposes only and should not be construed\n    as financial, legal, investment or other advice or recommendations of any kind.\n- summary: Not basis for securities transactions\n  text: KAYRROS REPORTS DO NOT CONTAIN ANY RECOMMENDATIONS\
  \ TO BUY OR SELL ANY SECURITIES OR COMMODITY INTERESTS\n    AND SHOULD NOT BE RELIED UPON AS THE BASIS FOR ANY TRANSACTIONS IN SECURITIES OR COMMODITY INTERESTS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kayrros/eligibility/kayrros-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Kayrros's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Geospatial
- Satellite Imagery
- Energy
- Environmental Intelligence
- Emissions
- Methane
- Analytics
- Climate
- Machine Learning
- Remote Sensing
---
