---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “You” or “your” mean you individually or the entity on behalf of which you are accessing or using the Services.
    type: individual
  minimum_age:
    text: you (a) are of the age of majority in your jurisdiction
    value: age of majority in your jurisdiction
  restricted_uses:
  - summary: Automated access (robots, scrapers)
    text: use any robot, spider, scraper, or other automated means to access or use the Services.
  - summary: Sale or advertisement of other products
    text: use the Services for the sale or advertisement of other products or services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right, in our sole discretion, to accept or reject your registration to create an Account and/or to access or use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FlyHomes
provenance_date: '2026-11-09'
provider_name: FlyHomes
provider_slug: flyhomes
slug: flyhomes-eligibility
source_date: '2026-11-09'
source_filename: flyhomes-eligibility.yml
source_heading: Eligibility
source_page: https://flyhomes.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FlyHomes\naid: flyhomes\nurl: https://flyhomes.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “You” or “your” mean you individually or the entity on behalf of which you are accessing or using the Services.\nrestricted_uses:\n- summary: Automated access (robots, scrapers)\n  text: use any robot, spider, scraper, or other automated means to access or use the Services.\n- summary: Sale or advertisement of other products\n  text: use the Services for the sale or advertisement of other products or services\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: We reserve the right, in our sole discretion, to accept or reject your registration to create an Account\n    and/or to access or use the Services.\nminimum_age:\n  value: age of majority in your jurisdiction\n  text: you (a) are of the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/flyhomes/eligibility/flyhomes-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from FlyHomes's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Mortgage
- Lending
- Fintech
- Financial Services
- Home Buying
---
