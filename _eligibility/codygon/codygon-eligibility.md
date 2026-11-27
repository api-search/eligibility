---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Services are intended for businesses and for users who are at least 18 years of age.
    type: business
  - text: you are at least 18 years of age and not a minor in the jurisdiction in which you reside
    type: individual
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: you will not use the Services for any illegal or unauthorized purpose
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
name: Codygon
provenance_date: '2026-11-09'
provider_name: Codygon
provider_slug: codygon
slug: codygon-eligibility
source_date: '2026-11-09'
source_filename: codygon-eligibility.yml
source_heading: Eligibility
source_page: https://codygon.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Codygon\naid: codygon\nurl: https://codygon.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: The Services are intended for businesses and for users who are at least 18 years of age.\n- type: individual\n  text: you are at least 18 years of age and not a minor in the jurisdiction in which you reside\n\
  restricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: you will not use the Services for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/codygon/eligibility/codygon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Codygon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Analytics
- Data Quality
- Enterprise
---
