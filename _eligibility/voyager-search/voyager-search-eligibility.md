---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Site ... if you are a person prohibited by the laws of the United States of America or any other country from receiving the services on the Site, including export and import control laws.
  minimum_age:
    text: 'You may not use the Site or accept the Terms if: (a) you are not of legal age to enter into a binding contract'
    value: null
  restricted_uses:
  - summary: Export-controlled persons
    text: you are a person prohibited by the laws of the United States of America or any other country from receiving the services on the Site, including export and import control laws.
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
name: Voyager Search
provenance_date: '2026-11-10'
provider_name: Voyager Search
provider_slug: voyager-search
slug: voyager-search-eligibility
source_date: '2026-11-10'
source_filename: voyager-search-eligibility.yml
source_heading: Eligibility
source_page: https://www.voyagersearch.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Voyager Search\naid: voyager-search\nurl: https://www.voyagersearch.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Site ... if you are a person prohibited by the laws of the United States of America\n    or any other country from receiving the services on the Site, including export and import control laws.\nentity_types: []\nrestricted_uses:\n- summary: Export-controlled persons\n  text: you are a person prohibited by the laws of the United States of America or any other country from receiving\n    the services on the Site, including export and\
  \ import control laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: 'You may not use the Site or accept the Terms if: (a) you are not of legal age to enter into a binding contract'\n"
source_yaml_url: https://artifacts.apis.io/voyager-search/eligibility/voyager-search-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Voyager Search's own page on 2026-11-10.
synthetic: false
tags:
- Geospatial
- Data Intelligence
- Enterprise
- Search
- Platform
- Company
---
