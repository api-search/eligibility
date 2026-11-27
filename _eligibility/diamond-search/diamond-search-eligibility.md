---
api_specs:
- filename: diamond-search-fullfeed-api-openapi.yml
  format: yaml
  label: Diamond Search Fullfeed API
  slug: diamond-search-fullfeed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diamond-search/openapi/diamond-search-fullfeed-api-openapi.yml
- filename: diamond-search-getreport3-api-openapi.yml
  format: yaml
  label: Diamond Search Getreport3 API
  slug: diamond-search-getreport3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diamond-search/openapi/diamond-search-getreport3-api-openapi.yml
- filename: diamond-search-labgrownfullfile-api-openapi.yml
  format: yaml
  label: Diamond Search Labgrownfullfile API
  slug: diamond-search-labgrownfullfile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diamond-search/openapi/diamond-search-labgrownfullfile-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: access to services for the facilitation of diamond transactions on the Web Site, restricted to Business to Business diamond transactions
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use without agreement
    text: for a commercial purpose not expressly sanctioned by a written agreement between you and IDEX ONLINE
  - summary: Competitive solicitation
    text: solicit or participate in the solicitation of our Visitors/Users/Guaranteed Diamond Transactions ® Members when such solicitation is for the benefit of any entity which could reasonably be construed to be or to become competitive with IDEX ONLINE
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
name: Diamond Search
provenance_date: '2026-11-09'
provider_name: Diamond Search
provider_slug: diamond-search
slug: diamond-search-eligibility
source_date: '2026-11-09'
source_filename: diamond-search-eligibility.yml
source_heading: Eligibility
source_page: http://www.idexonline.com/Conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Diamond Search\naid: diamond-search\nurl: http://www.idexonline.com/Conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: access to services for the facilitation of diamond transactions on the Web Site, restricted to Business\n    to Business diamond transactions\nrestricted_uses:\n- summary: Commercial use without agreement\n  text: for a commercial purpose not expressly sanctioned by a written agreement between you and IDEX ONLINE\n- summary: Competitive solicitation\n  text: solicit or participate in the solicitation of our Visitors/Users/Guaranteed\
  \ Diamond Transactions ® Members\n    when such solicitation is for the benefit of any entity which could reasonably be construed to be or to become\n    competitive with IDEX ONLINE\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/diamond-search/eligibility/diamond-search-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Diamond Search's own page on 2026-11-09.
synthetic: false
tags:
- Diamonds
- Lab Grown
- Pricing
- Trading
---
