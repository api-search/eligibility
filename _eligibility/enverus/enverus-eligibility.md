---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist supporting" country
  minimum_age:
    text: If you are not at least 13 years old, you may not use the Site at any time or in any manner or submit any information to the Company or the Site.
    value: '13'
  restricted_uses:
  - summary: Unauthorized activities
    text: Defame, abuse, harass, stalk, threaten, or otherwise violate the legal rights (such as rights of privacy and publicity) of others.
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
name: Enverus
provenance_date: '2026-11-09'
provider_name: Enverus
provider_slug: enverus
slug: enverus-eligibility
source_date: '2026-11-09'
source_filename: enverus-eligibility.yml
source_heading: Eligibility
source_page: https://www.enverus.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Enverus\naid: enverus\nurl: https://www.enverus.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government\n    embargo, or that has been designated by the U.S. Government as a \"terrorist supporting\" country\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized activities\n  text: Defame, abuse, harass, stalk, threaten, or otherwise violate the legal rights (such as rights of privacy\n    and publicity) of others.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are not at least 13 years old, you may not use the Site at any time or in any manner or submit any\n    information to the Company or the Site.\n"
source_yaml_url: https://artifacts.apis.io/enverus/eligibility/enverus-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Enverus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Oil and Gas
- Energy Data
- Analytics
- Market Intelligence
- Well Data
- Software-as-a-Service
- Direct Access
- Trading and Risk
- Data
- Geospatial
- Developer API
- Production Data
- Energy Intelligence
---
