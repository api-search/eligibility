---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity (“you”)
    type: individual
  minimum_age:
    text: you are not under the age of 13
    value: '13'
  restricted_uses:
  - summary: Commercial endeavors
    text: The Site may not be used in connection with any commercial endeavors except those that are specifically endorsed or approved by us.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: the Bank Partner has discretion to approve or deny your application for a Copper account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Copper Banking
provenance_date: '2026-11-09'
provider_name: Copper Banking
provider_slug: copper-banking
slug: copper-banking-eligibility
source_date: '2026-11-09'
source_filename: copper-banking-eligibility.yml
source_heading: Eligibility
source_page: https://www.getcopper.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Copper Banking\naid: copper-banking\nurl: https://www.getcopper.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity (“you”)\nrestricted_uses:\n- summary: Commercial endeavors\n  text: The Site may not be used in connection with any commercial endeavors except those that are\
  \ specifically\n    endorsed or approved by us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: the Bank Partner has discretion to approve or deny your application for a Copper account\nminimum_age:\n  value: '13'\n  text: you are not under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/copper-banking/eligibility/copper-banking-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Copper Banking's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Consumer Finance
- Financial Literacy
- Rewards
- Neobank
- Mobile Banking
- Teen Banking
- MCP
---
