---
api_specs:
- filename: back9ins-com-openapi-generated.yml
  format: yaml
  label: back9ins-com API
  slug: back9ins-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back9ins-com/openapi/_ae-authored/back9ins-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are located in a country embargoed by the United States, or are on the U.S. Treasury Department's list of Specially Designated Nationals you will not engage in commercial activities on BackNine (such as advertising or payments) or operate a Platform application or website.
  entity_types:
  - text: Unless expressly agreed otherwise in writing, all such parties are independent contractors or independent business entities
    type: business
  minimum_age:
    text: You will not use BackNine if you are under 18.
    value: '18'
  restricted_uses:
  - summary: Unlawful, misleading, malicious or discriminatory use
    text: You will not use BackNine to do anything unlawful, misleading, malicious, or discriminatory.
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
name: back9ins-com
provenance_date: '2026-11-09'
provider_name: back9ins-com
provider_slug: back9ins-com
slug: back9ins-com-eligibility
source_date: '2026-11-09'
source_filename: back9ins-com-eligibility.yml
source_heading: Eligibility
source_page: https://github.com/back9ins/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: back9ins-com\naid: back9ins-com\nurl: https://github.com/back9ins/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are located in a country embargoed by the United States, or are on the U.S. Treasury Department's\n    list of Specially Designated Nationals you will not engage in commercial activities on BackNine (such as advertising\n    or payments) or operate a Platform application or website.\nentity_types:\n- type: business\n  text: Unless expressly agreed otherwise in writing, all such parties are independent contractors or independent\n    business entities\nrestricted_uses:\n\
  - summary: Unlawful, misleading, malicious or discriminatory use\n  text: You will not use BackNine to do anything unlawful, misleading, malicious, or discriminatory.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You will not use BackNine if you are under 18.\n"
source_yaml_url: https://artifacts.apis.io/back9ins-com/eligibility/back9ins-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from back9ins-com's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Insurtech
- Software-as-a-Service
- B2B
- Life Insurance
---
