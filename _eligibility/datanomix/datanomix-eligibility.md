---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: 'you represent and warrant that: (1) you have the legal capacity'
    type: individual
  - text: whether personally or on behalf of an entity (“you”)
    type: business
  minimum_age:
    text: you are not a minor in the jurisdiction in which you reside
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: you will not use the Site for any illegal or unauthorized purpose
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
name: DataNomix
provenance_date: '2026-11-09'
provider_name: DataNomix
provider_slug: datanomix
slug: datanomix-eligibility
source_date: '2026-11-09'
source_filename: datanomix-eligibility.yml
source_heading: Eligibility
source_page: https://datanomix.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DataNomix\naid: datanomix\nurl: https://datanomix.io/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: 'you represent and warrant that: (1) you have the legal capacity'\n- type: business\n  text: whether personally or on behalf of an entity (“you”)\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text:\
  \ you will not use the Site for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not a minor in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/datanomix/eligibility/datanomix-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from DataNomix's own page on 2026-11-09.
synthetic: false
tags:
- Manufacturing
- Data Analytics
- IoT
- ERP Integration
- Real-Time Monitoring
---
