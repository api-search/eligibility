---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This website, and any associated information/social media/web app, is not intended to be used by or distributed to any person or entity in a jurisdiction or country where this would be contrary to local law or regulation.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Retail clients excluded
    text: Retail Clients (as defined by the FCA’s Conduct of Business Rules) are not permitted to use this website.
  - summary: Consumers excluded
    text: Consumers (as defined by the FCA) are not permitted to use this website.
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
name: Calastone
provenance_date: '2026-11-09'
provider_name: Calastone
provider_slug: calastone
slug: calastone-eligibility
source_date: '2026-11-09'
source_filename: calastone-eligibility.yml
source_heading: Eligibility
source_page: https://www.calastone.com/terms-of-website-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Calastone\naid: calastone\nurl: https://www.calastone.com/terms-of-website-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This website, and any associated information/social media/web app, is not intended to be used by or distributed\n    to any person or entity in a jurisdiction or country where this would be contrary to local law or regulation.\nentity_types: []\nrestricted_uses:\n- summary: Retail clients excluded\n  text: Retail Clients (as defined by the FCA’s Conduct of Business Rules) are not permitted to use this website.\n- summary: Consumers excluded\n  text: Consumers\
  \ (as defined by the FCA) are not permitted to use this website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/calastone/eligibility/calastone-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Calastone's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Fund
- Asset Management
- Fund Administration
- Financial Services
- Money Markets
- Settlement
- Tokenization
---
