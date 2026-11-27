---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Aunalytics makes no representation that content on the Website is appropriate or available for use outside the United States, its territories, possessions and protectorates.
  entity_types:
  - text: This is a general audience Website for adults. We will assume (and by using this Website you warrant that) you have legal capacity to enter into the agreement
    type: individual
  minimum_age:
    text: Interactive Areas are available for individuals aged 13 years or older.
    value: '13'
  restricted_uses:
  - summary: Export restrictions
    text: No software may be downloaded or otherwise exported or re-exported (A) into (or to a national or resident of) Cuba, Iraq, Libya, North Korea, Iran, Syria, or any other country to which the U.S. has embargoed goods
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
name: Aunalytics
provenance_date: '2026-11-09'
provider_name: Aunalytics
provider_slug: aunalytics
slug: aunalytics-eligibility
source_date: '2026-11-09'
source_filename: aunalytics-eligibility.yml
source_heading: Eligibility
source_page: https://www.aunalytics.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aunalytics\naid: aunalytics\nurl: https://www.aunalytics.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Aunalytics makes no representation that content on the Website is appropriate or available for use outside\n    the United States, its territories, possessions and protectorates.\nentity_types:\n- type: individual\n  text: This is a general audience Website for adults. We will assume (and by using this Website you warrant that)\n    you have legal capacity to enter into the agreement\nrestricted_uses:\n- summary: Export restrictions\n  text:\
  \ No software may be downloaded or otherwise exported or re-exported (A) into (or to a national or resident\n    of) Cuba, Iraq, Libya, North Korea, Iran, Syria, or any other country to which the U.S. has embargoed goods\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Interactive Areas are available for individuals aged 13 years or older.\n"
source_yaml_url: https://artifacts.apis.io/aunalytics/eligibility/aunalytics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Aunalytics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Financial Services
- Data Analytics
- Cloud
---
